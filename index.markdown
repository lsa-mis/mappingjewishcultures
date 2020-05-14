---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---
<div class="about-section">
  <div class='wrapper'>
      <div class='section-title-and-cta'>
        <a href='about.html'><h2 class='section-title'>About</h2></a>
        <a href='{{ "/about/" | relative_url }}' class='homepage-call-to-action'>Learn More ></a>
      </div>
      <p class='section-description'>This project encourages you to examine the confluence between cafés, the urban environment, and the creativity of multilingual Jewish communities. The mapping and digital storytelling tools you will find here are based on extensive research done for Prof. Shachar Pinsker’s book <a href='https://nyupress.org/9781479874385/a-rich-brew/' class='special-link' id='title-link' target='blank'>A Rich Brew: How Cafés Created Modern Jewish Culture</a> (NYU Press, 2018). Consider this site a companion resource, or a standalone project for you to experience.</p>
  </div>
</div>

<div class='explore-section'>      
  <div class='explore-section-right'>
    <a href='{{ "/cities/" | relative_url }}'><div class='explore-section-image' id='test-thumbnail'>
        <img class='explore-cities-img' src='{{site.baseurl}}/images/explore-cities.jpg'>
        <h3 class='explore-link'>Cities</h3>
        <div class = 'source-credit'>Postcard of Café Robina, Odessa, early twentieth century</div>
    </div></a>

    <a href='{{ "/people/" | relative_url }}'><div class='explore-section-image'>
        <img class='explore-cities-img' src='{{site.baseurl}}/images/explore-people-bg-edited.jpg'>
        <h3 class='explore-link'>People</h3>
        <div class = 'source-credit'>Caricature by Joseph Foshko, YIVO archive</div>
    </div></a>

    <a href='{{ "/time/" | relative_url }}'><div class='explore-section-image'>
        <img class='explore-cities-img' src='{{site.baseurl}}/images/ny_illustration.jpg'>
        <h3 class='explore-link'>Time</h3>
        <div class = 'source-credit'>
          Illustration by Rutu Modan, The New Yorker Magazine
        </div>
    </div></a>
  </div>

  <div class='explore-section-left'>
    <a href='{{ "/explore/" | relative_url }}' id='explore-section-title-adjusted'><h2 class='section-title'>Explore</h2></a>
    <div class='explore-section-description'>
        <p>You can examine Jewish café culture through cities, people, and time. In “Cities,” you will explore cafés geographically. In “People” you will learn about the writers, artists, journalists, activists, and actors. “Time” will open a timeline of the cafés established from the early 19th century to present.</p>
    </div>
  </div> 
</div>

<div class='stories-section'>
  <div class='wrapper'>
    <div class='section-title-and-cta'>
        <a href='{{ "/stories/" | relative_url }}'><h2 class='section-title'>Stories</h2></a>
        <a href='{{ "/stories/" | relative_url }}' class='homepage-call-to-action'>View More ></a>
    </div>
    <p class='section-description'>Learn more about key people and events which shaped Jewish culture in the café by exploring StoryMaps which offer detailed narratives incorporating historical maps, photographs, paintings, and literature.</p>
  </div>

  <div class='wrapper'>
    <div class='featured-stories'>
      <a href='women-cafe-story.html'><div class= 'story-thumbnail'>
          <img src='{{site.baseurl}}/images/stories/women.png'>
          <h3 class='story-link' id='women'>Women in the Café</h3>
          <div class='source-credit'>
            Leah Goldberg, 1935 (Courtesy of the Ganzim Institute, Tel Aviv, and Yair Landau)
          </div>
      </div></a>
      <a href='warsaw-story.html'><div class= 'story-thumbnail'>
          <img src='{{site.baseurl}}/images/stories/warsaw.jpg'>
          <h3 class='story-link' id='warsaw'>Jewish Café Culture in Warsaw</h3>
          <div class='source-credit'>Cafe Scene, 1934, Moshe Rynecki, 36.1 x 50 cm</div>
      </div></a>
      <a href='sholem-story.html'><div class= 'story-thumbnail'>
          <img src='{{site.baseurl}}/images/stories/sholem.jpg'>
          <h3 class='story-link' id='sholem'>The Travels of Sholem Aleichem and Menakhem Mendl</h3>
          <div class='source-credit'>http://sholemaleichem.org/writing-desk/</div>
          </div></a>
      <a href='yiddish-story.html' id='sholem-hide'><div class= 'story-thumbnail'>
          <img src='{{site.baseurl}}/images/stories/cabaret.jpg'>
          <h3 class='story-link' id='cabaret'>Yiddish Theater and Cabaret</h3>
          <div class='source-credit'>https://collections.mcny.org/Collection/Grand-Theater,-Jacob-B.-Adler,-King-Lear-close-up.-2F3XC5UNBCDZ.html</div>
      </div></a>
    </div>
  </div>  
</div>