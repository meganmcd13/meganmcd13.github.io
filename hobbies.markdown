---
layout: page
title: Hobbies
permalink: /hobbies/
---

My main hobbies are <a href="#music">music</a>, <a href="#hiking">hiking</a>, and <a href="#fiber-arts">fiber arts</a>. I've been playing the flute (among other instruments) since I was in fourth grade, and music has been a huge part of my life ever since. I also enjoy spending time outdoors and exploring nature. Fiber arts are a more recent endeavor, however. I learned to crochet in 2020 during the pandemic, and I recently picked up knitting as well. You can check out some of my performances, hikes, and projects below!

<h2 id="hiking">Recent hikes: </h2>

<div class="posts-list">
  {% for post in site.categories.hike %}
    <article class="post">
      <h3>{{ post.title }}</h3>
      <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
      {{ post.excerpt | markdownify }}
    </article>
  {% endfor %}
</div>

<br><br>
<h2 id="fiber-arts">Fiber arts projects I'm working on: </h2>

<div class="posts-list">
  {% for post in site.categories.fiber %}
    <article class="post">
      <h3>{{ post.title }}</h3>
      <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
      {{ post.excerpt | markdownify }}
    </article>
  {% endfor %}
</div>

<br><br>
<h2 id="music">Music performances: </h2>

<div class="posts-list">
  {% for post in site.categories.music %}
    <article class="post">
      <h3>{{ post.title }}</h3>
      <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
      {{ post.excerpt | markdownify }}
    </article>
  {% endfor %}
</div>