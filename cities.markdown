---
layout: page
title: Cities
permalink: /cities/
---
<div class='cities'>
  <div class='wrapper'>
    <h2 class='section-title' id='people-title'>Cities</h2>
    <div id="slide">
      <div style="background-color: white; padding: 10px;">
        <h2 style="font-size: 1.5em;">How to use the Browse by City tool</h2>
        <hr >
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
        <br>
        <button class="slide_close">Close</button>
        <br>
      </div>
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
    </div>
  </div>
</div>

<!-- [jekyll-organization]: https://github.com/jekyll -->
