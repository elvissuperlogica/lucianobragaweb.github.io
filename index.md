---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: now/index
title: Programador Web Luciano Braga
menu: false
---

<h3 class="title">Web Developer</h3>
<h5 class="description">In my life I try to create new things, to bet on personal projects and in the future.</h5>

<h3>Posts</h3>
<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
