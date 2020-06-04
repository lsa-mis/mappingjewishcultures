---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
permalink: /
---
<div class="about-section">
      <p class='section-description'>This project encourages you to examine the confluence between cafés, the urban environment, and the creativity of multilingual Jewish communities. The mapping and digital storytelling tools you will find here are based on extensive research done for Prof. Shachar Pinsker’s book <a href='https://nyupress.org/9781479874385/a-rich-brew/' class='book-title-link' id='title-link' target='blank'>A Rich Brew: How Cafés Created Modern Jewish Culture</a> (NYU Press, 2018). Consider this site a companion resource, or a standalone project for you to experience.
      </p>
</div>

<div>
  <h2>Explore</h2>

  <div class="explore-col-wrapper">
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/index-cities.png' alt="antique city map">
      <div class="explore-col-text">
        <a href='{{ "cities" | relative_url }}'><span class="explore-col-title">Cities</span>
        <p class="explore-text">Experience the culture geographically by viewing cafes and taking guided tours though digital mapping.</p>
        </a>
      </div>
    </div>
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/people/People5.png' alt="people network map showing 7 nodes">
      <div class="explore-col-text">
        <a href='{{ "people" | relative_url }}'><span class="explore-col-title">People</span>
        <p class="explore-text">Learn more about writers, artists, journalists, activists, and actors. by discovering connections between people and cafes.</p>
        </a>
      </div>
    </div>
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/index-time.png' alt="historic drawing of cafe patrons">
      <div class="explore-col-text">
        <a href='{{ "time" | relative_url }}'><span class="explore-col-title">Time</span>
        <p class="explore-text">Witness the expansion of cafés in Jewish culture dating back to the 1800s with a timeline.</p>
        </a>
      </div>
    </div>
  </div>
</div>

<h2>Stories</h2>
<p>Choose a StoryMap to learn more about key people and events which shaped Jewish culture in the café.  Each story offers detailed narratives incorporating historical maps, photographs, paintings, and literature.</p>

<div class="story-col-wrapper">
  <div class="story-col">
   <a class="story-page-link" href='{{ "stories/women-cafe-story" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/womenbtn.png' alt="Women in the Café">
    </a>
    <div class='source-credit'>Leah Goldberg, 1935 (Courtesy of the Ganzim Institute, Tel Aviv, and Yair Landau)</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/warsaw-story" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/warsawbtn.png' alt="Jewish Café Culture in Warsaw">
    </a>
    <div class='source-credit'>Cafe Scene, 1934, Moshe Rynecki</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/sholem-story" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/travelbtn.png' alt="The Travels of Sholem Aleichem and Menakhem Mendl">
    </a>
    <div class='source-credit'>http://sholemaleichem.org/writing-desk/</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/berlin-story" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/berlinbtn.png' alt="Jewish Café Culture in Berlin">
        </a>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/newyork-story" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/newyorkbtn.png' alt="Jewish Café Culture in New York">
        </a>
  </div>
</div>
<div class="bottom-btn" align="center">
 <button id="stories-button"><a href='{{ "/stories/" | relative_url }}'>View All Stories</a></button>
</div>