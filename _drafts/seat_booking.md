---
title: "Book a seat"
layout: default
textcolor: blue-grey-text text-lighten-5
bgcolor: blue darken-4
permalink: /seat-booking/
---

# Book a seat at church.

## This form will email church on submission
<div class="row">
  <form action="https://formspree.io/woodcock3@gmail.com" class="col s12" form method="POST" enctype="multipart/form-data" name="EmailTestForm">
    <div class="row">
      <div class="input-field col s12 m6 offset-3">
        <input type="text" class="datepicker">
        <label> Date attending church service</label>
      </div>
      <div class="input-field col s12"> 
        <div class="input-field">
          <select>
            <option value="" disabled selected>Select no. of people</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
          </select>
          <label>Number of people from your household/bubble comming to church</label>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="input-field col s12 m6">
        <form action="#">
          <p>
            <label>
              <input class="with-gap" name="seat-type" type="radio" checked />
              <span>Prefer ground floor seat(s)</span>
            </label>
          </p>
          <p>
            <label>
              <input class="with-gap" name="seat-type" type="radio" />
              <span>Prefer balcony seat(s)</span>
            </label>
          </p>
          <p>
            <label>
              <input class="with-gap" name="seat-type" type="radio"  />
              <span>No preference</span>
            </label>
          </p>
        </form>
      </div>
    </div>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
        <label for="icon_prefix">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
        <label for="icon_prefix">Surname</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_telephone" type="tel" class="validate">
        <label for="icon_telephone">Telephone</label>
      </div>
    </div>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
        <label for="icon_prefix">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
         <label for="icon_prefix">Surname</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_telephone" type="tel" class="validate">
        <label for="icon_telephone">Telephone</label>
      </div>
    </div>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
        <label for="icon_prefix">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
         <label for="icon_prefix">Surname</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_telephone" type="tel" class="validate">
        <label for="icon_telephone">Telephone</label>
      </div>
    </div>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
        <label for="icon_prefix">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_prefix" type="text" class="validate">
         <label for="icon_prefix">Surname</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="icon_telephone" type="tel" class="validate">
        <label for="icon_telephone">Telephone</label>
      </div>
    </div>
    <button class="btn-large waves-effect waves-light" type="submit" name="action">Submit
    <i class="material-icons right">send</i>
    </button>
  </form>
</div>


