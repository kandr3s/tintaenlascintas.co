---
layout: base 
title: "Clásicos"
permalink: "/clasicos"
---
¿Qué define un clásico? Los críticos aún no logran ponerse de acuerdo. Para nosotros los clásicos son esos discos que creemos necesitan estar en la colección de todo el mundo. Aquí hemos mencionado algunos de ellos.
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
 