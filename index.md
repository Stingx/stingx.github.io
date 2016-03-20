---
layout: page
title: 一个刚出生的网站
tagline: 目前还没什么用
---
{% include JB/setup %}

这个是简介 

刚完成的网站.折腾了好久...这主题的作者虽然说是在完善中,但是我觉得已经好好了,而且还没弄完善正好让我自己来改改.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
          <span>{{ post.excerpt }}</span>
    </li>

  {% endfor %}
</ul>




