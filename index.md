---
layout: page
title: Blog
tagline: dfchx
---
{% include JB/setup %}

[my github] (https://github.com/danfengchaoxi)

## To-Do

出问题啦！

## Doing

解决ing。


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
