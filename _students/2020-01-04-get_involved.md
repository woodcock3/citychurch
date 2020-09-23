---
title: "Get involved"
bg: thursday
color: white
border-color: friday
fa-icon: cog
collection_type: "students"
layout: all_collections
---

<div class="section-lines section-top section-left"></div>
{% for activity in site.data.agenda.thursday %}
  {% capture thecycle %}{% cycle 'even', 'odd' %}{% endcapture %}
  {% if thecycle == 'odd' %}
  {% if activity == site.data.agenda.thursday.last %}
  <div class="activity section-left">
  {% else %}
  <div class="activity section-left section-bottom">
  {% endif %}
    <div class="row activity-info-wrapper valign-wrapper">
      <div class="col m12 activity-info">
        <h2 class="activity-title"> {{ activity.title }} </h2>
        <div class="col m12 activity-time">
          <i class="fa fa-clock-o"></i> <span> {{ activity.time }} </span>
        </div>
        <div class="col m12 activity-place">
          <i class="fa fa-map-marker"></i> <span> {{ activity.place }} </span>
        </div>
        <p class="col m12 activity-desc"> {{ activity.text }} </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="{{ activity.typeform }}" onmouseover="this.href=this.href.replace('@@','.')">Email Student Team</a>
        {% endif %}
      </div>
    </div>
  </div>
  {% else %}
  {% if activity == site.data.agenda.thursday.last %}
  <div class="activity section-right">
  {% else %}
  <div class="activity section-right section-bottom">
  {% endif %}
    <div class="row activity-info-wrapper valign-wrapper">
      <div class="col m12 activity-info">
        <h2 class="activity-title"> {{ activity.title }} </h2>
        <p class="col m12 activity-desc"> {{ activity.text }} </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="{{ activity.typeform }}" target="blank">Find a CU</a>
        {% endif %}
      </div>
    </div>
  </div>
  {% endif %}
{% endfor %}
{% if thecycle == 'even' %}
<div class="section-lines section-bottom section-left"></div>
  {% else %}
<div class="section-lines section-bottom section-right"></div>
{% endif %}
