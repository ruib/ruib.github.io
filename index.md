---
title: let me think..
layout: page
---
# Hello World!

Saying hello to the world. More to come later.

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

