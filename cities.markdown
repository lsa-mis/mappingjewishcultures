---
layout: page
title: Cities
permalink: /cities/
---

<script src="https://js.arcgis.com/4.8/"></script>
  <script src="https://code.jquery.com/jquery-1.8.2.min.js"></script>
  <!-- <script src="https://cdn.rawgit.com/vast-engineering/jquery-popup-overlay/1.7.13/jquery.popupoverlay.js"></script> -->
  <!-- <script>
      $(document).ready(function() {
        // Initialize the plugin
          $('#slide').popup({
        outline: false, // optional
        focusdelay: 1000,
        autoopen: true,
        blur: true,
        vertical: 'center' //optional 
      });
      console.log('thing?');
      });
    </script> -->

  <script>
      var dojoConfig = {
          has: {
              "esri-featurelayer-webgl": 1,
              "esri-promise-compatibility": 1

          }
      };
  </script>
  <style>
    /* html,
    body, */

    /* #slide,
    #slide_wrapper {
      transition: all 0.3s ease-out;
      height: 100%;
      width: 50%;
    }
    #slide {
      transform: translateX(25%) translateY(10%);
      font: Arial;
      color: black;
    }
    .popup_visible #slide {
      transform: translateX(0%) translateY(10%);
    } */

  </style>
<script src="{{site.baseurl}}/assets/js/cities.js"></script>
<h1 class='section-title' id='people-title'>Explore Cities</h1>
<div id="viewDiv"></div>
<div id="search">
  <div id ="yearRangeContainer">
    <div id="yearRange" name="yearRange">
      <div id="yearRangeLabels">
            <input type="number" id="startYear" class="sliderLabel" onchange="updateSlider(this)"/>
          <input type="number" id="endYear" class="sliderLabel" onchange="updateSlider(this)"/>
      </div>
    </div>
  </div>
</div>
<div>
  <p>Explore an interactive map of cafés and landmarks important to Jewish culture in New York, Berlin, Odessa, Warsaw, Vienna, and Tel Aviv. This map can be adjusted to show points in a single city during a specfic timeframe or opt for a story map to take a guided tour of a city’s impact on modern Jewish culture.</p>
</div>

<h2>View Stories</h2>
<div class="button-collection">
  <button class="story-button-small"><a href='{{ "stories/berlin-story" | relative_url }}'>Berlin</a></button>
  <button class="story-button-small"><a href='{{ "stories/newyork-story" | relative_url }}'>New york</a></button>
  <button class="story-button-small"><a href='http://scalar.usc.edu/works/odessa/a-brief-history-of-odessa?path=caf-culture-in-the-jewish-city' target='blank'>Odessa</a></button>
  <button class="story-button-small"><a href='{{ "stories/vienna-story" | relative_url }}'>Vienna</a></button>
  <button class="story-button-small"><a href='{{ "stories/yiddish-story" | relative_url }}'>Jerusalem</a></button>
  <button class="story-button-small"><a href='{{ "stories/telaviv-story" | relative_url }}'>Telaviv</a></button>
</div>

<h3>How to use the Browse by City tool</h3>


<div id="slide">
  <div style="background-color: white; padding: 10px;">
    <!-- <h2 style="font-size: 1.5em;">How to use the Browse by City tool</h2>
    <hr > -->
    Click on a city icon <img src ="{{site.baseurl}}/images/cities_popup/1.png"> to explore cafes in space and time. Opt to either view a <img src ="{{site.baseurl}}/images/cities_popup/2.png"> for a curated tour of a city, or select <img src ="{{site.baseurl}}/images/cities_popup/3.png">
    <br><br><br>
    <b>Click on café markers to view detailed information about cafes:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/4.png">
    <br><br>
    <b>Use the time slider to filter by year:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/5.png">
    <br><br>
    <b>Select items in the Layer window to display historic city maps:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/6.png">
    <br><br>
    Use the globe button <img src ="{{site.baseurl}}/images/cities_popup/7.png"> to return to the full extent of the map. 
    <!-- <br>
    <button class="slide_close">Close</button>
    <br> -->
  </div>
  <!-- <div id="viewDiv"></div>
  <div id="search">
    <div id ="yearRangeContainer">
      <div id="yearRange" name="yearRange">
        <div id="yearRangeLabels">
              <input type="number" id="startYear" class="sliderLabel" onchange="updateSlider(this)"/>
            <input type="number" id="endYear" class="sliderLabel" onchange="updateSlider(this)"/>
        </div>
      </div>
    </div>
  </div> -->
</div>
