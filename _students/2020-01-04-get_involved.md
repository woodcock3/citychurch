---
title: "Get involved"
bg: thursday
color: white
border-color: friday
fa-icon: bullhorn
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
      <div class="col m3 activity-img valign">
        <img  src="img/{{ activity.image }}" alt="{{ activity.title }}">
      </div>
      <div class="col m9 activity-info">
        <h4 class="activity-title">Growth Groups</h4>
        <div class="col s12 activity-time">
          <i class="fa fa-clock-o"></i> <span> 7.45 or 8pm midweek </span>
        </div>
        <div class="col s12 activity-place">
          <i class="fa fa-map-marker"></i> <span> We’ve got two small group bible studies in North Leeds. </span>
        </div>
        <p class="col m12 activity-desc"> If you want to come along but need a lift, the Student Team will sort it out. </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="{{ activity.typeform }}" target="blank">Inscrio</a>
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
      <div class="col m9 activity-info">
        <h4 class="activity-title"> Christian Union </h4>
        <div class="col s12 activity-time">
          <i class="fa fa-clock-o"></i> <span> {{ activity.time }} </span>
        </div>
        <div class="col s12 activity-place">
          <i class="fa fa-map-marker"></i> <span> {{ activity.place }} </span>
        </div>
        <p class="col m12 activity-desc"> The CU is a fantastic opportunity to tell others about Christ and to be encouraged so, if your university has one please get involved! </p>
        {% if activity.typeform %}
        <a class="waves-effect waves-light btn bg-{{ page.border-color }}" href="https://www.uccf.org.uk/search?q=leeds" target="blank">Find a CU</a>
        {% endif %}
      </div>
      <div class="col m3 activity-img valign">
        <img  src="img/{{ activity.image }}" alt="{{activity.title}}">
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
