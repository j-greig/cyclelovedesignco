---
layout: page
title: Articles
subtitle:
permalink: /articles/
---
<ul>
   {% for post in site.posts %}
   <article class="mb4">
      <a href="{{ post.url }}"><h3 class="mb0 measure">{{ post.title }}</h3></a>
      <p>{{ post.subtitle }}</p>
    </article>
   {% endfor %}
</ul>
