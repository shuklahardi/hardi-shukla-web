---
layout: home
title: "Blog"
permalink: "/blog/"
---


<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

