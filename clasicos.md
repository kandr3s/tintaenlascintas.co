---
layout: base 
title: "Clásicos"
permalink: "/clasicos"
---
<div class="grid-container">
  {% for post in site.posts %}
  {% if post.category == "Clásicos" %}
  <article class="post-listing">
    <a class="post-title" href="{{ post.url }}">{{ post.title }}</a>
    <div class="album-art-container">
      <div class="album-art-frame">
        <img class="album-art" src="{{ post.image }}" alt="{{ post.title }}">
      </div>
    </div>
  </article>
  {% endif %}
  {% endfor %}
</div>
 