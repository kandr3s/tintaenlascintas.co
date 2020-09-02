---
layout: page
title: Publicaciones
---
<div class="grid-container">
  {% for post in site.posts %}
  <article class="post-listing">
    <a class="post-title" href="{{ post.url }}">{{ post.title }}</a>
    <div class="album-art-container">
      <div class="album-art-frame">
        <img class="album-art" src="{{ post.image }}" alt="{{ post.title }}">
      </div>
    </div>
    <!--div class="post-image">
      <a href="{{ post.url }}">
      <img src="{{ post.image }}" alt="{{ post.title }}"></a>
    </div-->
  </article>
  {% endfor %}
</div>