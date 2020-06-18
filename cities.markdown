---
layout: page
title: Cities
description: >- 
  Explore cities like Odessa, Warsaw, New York City, and Tel Aviv to uncover a network of interconnected cafés that were central to the modern Jewish experience.
permalink: /cities/
---

<h1 class='section-title' id='people-title'>Explore Cities</h1>
<div>
  <p>Explore an interactive map of cafés and landmarks important to Jewish culture in New York, Berlin, Odessa, Warsaw, Vienna, and Tel Aviv. This map can be adjusted to show points in a single city during a specfic timeframe or opt for a story map to take a guided tour of a city’s impact on modern Jewish culture.</p>
</div>
<div class="time-wrapper">
  <iframe title="World map" src="{{site.baseurl}}/cities-raw/cities-raw.html" scrolling="yes" width="100%" height="100%" frameborder="0">
    <div id="viewDiv"></div>
    <div id="search">
      <div id ="yearRangeContainer">
        <div id="yearRange" name="yearRange">
          <div id="yearRangeLabels">
              <label for="startYear"></label>
              <input type="number" id="startYear" class="sliderLabel" onchange="updateSlider(this)"/>
              <label for="endYear"></label>
              <input type="number" id="endYear" class="sliderLabel" onchange="updateSlider(this)"/>
          </div>
        </div>
      </div>
    </div>
  </iframe>
</div>
<h2>How to use the Browse by City tool</h2>
<div id="slideold">
  <div style="background-color: white; padding: 10px;">
    Click on a city icon <img src ="{{site.baseurl}}/images/cities_popup/1.png" alt="red map pin"> to explore cafes in space and time. Opt to either view a <img src ="{{site.baseurl}}/images/cities_popup/2.png" alt="underlined story map text"> for a curated tour of a city, or select <img src ="{{site.baseurl}}/images/cities_popup/3.png" alt="zoom to city icon">
    <br><br><br>
    <b>Click on café markers to view detailed information about cafes:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/4.png" alt="Example of city details pop-up information">
    <br><br>
    <b>Use the time slider to filter by year:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/5.png" alt="Example of time slider showing 1800 and 2000 range">
    <br><br>
    <b>Select items in the Layer window to display historic city maps:</b>
    <br>
    <img src ="{{site.baseurl}}/images/cities_popup/6.png" alt="Example of selection dropdown for displaying other maps">
    <br><br>
    Use the globe button <img src ="{{site.baseurl}}/images/cities_popup/7.png" alt="Globe icon"> to return to the full extent of the map. 
  </div>
</div>

<h2>View Stories</h2>
<div class="button-collection">
  <button class="story-button-small"><a href='{{ "stories/berlin-story" | relative_url }}'>Berlin</a></button>
  <button class="story-button-small"><a href='{{ "stories/newyork-story" | relative_url }}'>New York</a></button>
  <button class="story-button-small"><a href='http://scalar.usc.edu/works/odessa/a-brief-history-of-odessa?path=caf-culture-in-the-jewish-city' target='blank'>Odessa</a></button>
  <button class="story-button-small"><a href='{{ "stories/vienna-story" | relative_url }}'>Vienna</a></button>
  <button class="story-button-small"><a href='{{ "stories/yiddish-story" | relative_url }}'>Jerusalem</a></button>
  <button class="story-button-small"><a href='{{ "stories/telaviv-story" | relative_url }}'>Telaviv</a></button>
</div>