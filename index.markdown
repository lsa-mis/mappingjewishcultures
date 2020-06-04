---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
permalink: /
---
<div class="about-section">
  <!-- <div class='wrapper'> -->
      <p class='section-description'>This project encourages you to examine the confluence between cafés, the urban environment, and the creativity of multilingual Jewish communities. The mapping and digital storytelling tools you will find here are based on extensive research done for Prof. Shachar Pinsker’s book <a href='https://nyupress.org/9781479874385/a-rich-brew/' class='book-title-link' id='title-link' target='blank'>A Rich Brew: How Cafés Created Modern Jewish Culture</a> (NYU Press, 2018). Consider this site a companion resource, or a standalone project for you to experience.
      </p>
  <!-- </div> -->
</div>

<div>
  <h2>Explore</h2>

  <div class="explore-col-wrapper">
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/explore-cities.jpg'>
      <div class="explore-col-text">
        <span class="explore-col-title">Cities</span>
        <p>Experience the culture geographically by viewing cafes and taking guided tours though digital mapping.</p>
      </div>
    </div>
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/people/people5.png'>
      <div class="explore-col-text">
        <span class="explore-col-title">People</span>
        <p>Experience the culture geographically by viewing cafes and taking guided tours though digital mapping.</p>
      </div>
    </div>
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/ny_illustration.jpg'>
      <div class="explore-col-text">
        <span class="explore-col-title">Time</span>
        <p>Experience the culture geographically by viewing cafes and taking guided tours though digital mapping.</p>
      </div>
    </div>
    <!-- <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/explore-people-bg-edited.jpg'>
      <span class="explore-col-title">People</span>
      <p>Learn more about writers, artists, journalists, activists, and actors. by discovering connections between people and cafes </p>
    </div>
    <div class="explore-col">
      <img class="explore-element-image" src='{{site.baseurl}}/images/ny_illustration.jpg'>
      <span class="explore-col-title">Time</span>
      <p>Witness the expansion of cafés in Jewish culture dating back to the 1800s with a timeline</p>
    </div> -->
    <!-- <div class="explore-col">
      <a class="explore-page-link" href='{{ "/people/" | relative_url }}'>People
      <img class="explore-element-image" src='{{site.baseurl}}/images/explore-people-bg-edited.jpg'></a> 
    </div>
    <div class="explore-col">
      <a class="explore-page-link" href='{{ "/time/" | relative_url }}'>Time
      <img class="explore-element-image" src='{{site.baseurl}}/images/ny_illustration.jpg'></a>
    </div> -->
  </div>
</div>

<h2>Stories</h2>
<p>Choose a StoryMap to learn more about key people and events which shaped Jewish culture in the café.  Each story offers detailed narratives incorporating historical maps, photographs, paintings, and literature.</p>

<div class="story-col-wrapper">
  <div class="story-col">
   <a class="story-page-link" href='{{ "stories/women-cafe-story.html" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/womenbtn.png' alt="Women in the Café">
          <!-- Women in the Café -->
    </a>
    <div class='source-credit'>Leah Goldberg, 1935 (Courtesy of the Ganzim Institute, Tel Aviv, and Yair Landau)</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/warsaw-story.html" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/warsawbtn.png' alt="Jewish Café Culture in Warsaw">
        <!-- Jewish Café Culture in Warsaw -->
        </a>
    <div class='source-credit'>Cafe Scene, 1934, Moshe Rynecki, 36.1 x 50 cm</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/sholem-story.html" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/travelbtn.png' alt="The Travels of Sholem Aleichem and Menakhem Mendl">
        <!-- The Travels of Sholem Aleichem and Menakhem Mendl -->
        </a>
    <div class='source-credit'>http://sholemaleichem.org/writing-desk/</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/berlin-story.html" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/berlinbtn.png' alt="Yiddish Theater and Cabaret">
        <!-- Yiddish Theater and Cabaret -->
        </a>
    <div class='source-credit'>https://collections.mcny.org/Collection/Grand-Theater,-Jacob-B.-Adler,-King-Lear-close-up.-2F3XC5UNBCDZ.html</div>
  </div>
  <div class="story-col">
    <a class="story-page-link" href='{{ "stories/newyork-story.html" | relative_url }}'>
      <img class="story-element-image" src='{{site.baseurl}}/images/newyorkbtn.png' alt="Yiddish Theater and Cabaret">
        <!-- Yiddish Theater and Cabaret -->
        </a>
    <div class='source-credit'>https://collections.mcny.org/Collection/Grand-Theater,-Jacob-B.-Adler,-King-Lear-close-up.-2F3XC5UNBCDZ.html</div>
  </div>
</div>
<div class="bottom-btn" align="center">
 <button id="stories-button"><a href='{{ "/stories/" | relative_url }}'>View All Stories</a></button>
</div>