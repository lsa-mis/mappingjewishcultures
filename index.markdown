---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
description: >- 
  Experience Jewish cultural history by examining the confluence between cafés, the urban environment, and the creativity of multilingual European communities. An extension of the research presented in A Rich Brew, mapping and digital storytelling tools on the site provides a deeper, illustrative look into how cafes and social spaces helped to shape Jewish culture.
permalink: /
---
<div class="about-section">
      <p class='section-description-index'>This project encourages you to examine the confluence between cafés, the urban environment, and the creativity of multilingual Jewish communities. The mapping and digital storytelling tools you will find here are based on extensive research done for Prof. Shachar Pinsker’s book <a href='https://nyupress.org/9781479874385/a-rich-brew/' class='book-title-link' id='title-link' target='blank'>A Rich Brew: How Cafés Created Modern Jewish Culture</a> (NYU Press, 2018). Consider this site a companion resource, or a standalone project for you to experience.
      </p>
</div>

<div>
  <h2>Explore</h2>

  <div class="explore-col-wrapper">
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/index-cities.png' alt="antique city map">
      <div class="explore-col-text">
        <a href='{{ "cities" | relative_url }}'><span class="explore-col-title">Cities</span>
        <p class="explore-text">Experience the culture geographically by viewing cafes and taking guided tours through digital mapping.</p>
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
    <a href='{{ "stories/women-cafe-story" | relative_url }}'>
      <div class="box">
        <img class="story-element-image" src='{{site.baseurl}}/images/stories/women.png' alt="Women smoking at a table in a café">
        <div class="text">Women in the Café<br>&nbsp;</div>
      </div>
    </a> 
    <div class='source-credit'>Leah Goldberg, 1935 (Courtesy of the Ganzim Institute, Tel Aviv, and Yair Landau)</div>
  </div>
  <div class="story-col">
    <a href='{{ "stories/warsaw-story" | relative_url }}'>
      <div class="box">
        <img class="story-element-image" src='{{site.baseurl}}/images/stories/warsaw.jpg' alt="Watercolor painting of patrons at a café counter">
        <div class="text">Jewish Café Culture<br> in Warsaw</div>
      </div>
    </a> 
    <div class='source-credit'>Cafe Scene, 1934, Moshe Rynecki</div>
  </div>
  <div class="story-col">
    <a href='{{ "stories/sholem-story" | relative_url }}'>
      <div class="box">
        <img class="story-element-image" src='{{site.baseurl}}/images/stories/sholem.jpg' alt="Middle aged man with round eye glasses sitting at a writing desk">
        <div class="text">The Travels of Sholem Aleichem and Menakhem Mendl</div>
      </div>
    </a> 
    <div class='source-credit'><a href="http://sholemaleichem.org/writing-desk/">Sholem Aleichem</a></div>
  </div>
  <div class="story-col">
    <a href='{{ "stories/berlin-story" | relative_url }}'>
      <div class="box">
        <img class="story-element-image" src='{{site.baseurl}}/images/stories/Berlin.jpg' alt="Watercolor of a birds-eye view of a cafe with multiple tables and patrons">
        <div class="text">Jewish Café Culture<br> in Berlin</div>
      </div>
    </a>
    <div class='source-credit'><a href="https://www.ullsteinbild.de/?82231788017539342720">Romanisches Cafe, Berlin. Ullstein Bild.</a></div>
  </div>
  <div class="story-col">
    <a href='{{ "stories/newyork-story" | relative_url }}'>
      <div class="box">
        <img class="story-element-image" src='{{site.baseurl}}/images/stories/New-York.png' alt="Early black and white photograph of men standing together observing something">
        <div class="text">Jewish Café Culture<br> in New York</div>
      </div>
    </a> 
  </div>
</div>




<div class="bottom-btn" align="center">
 <button id="stories-button"><a href='{{ "/stories/" | relative_url }}'>View All Stories</a></button>
</div>