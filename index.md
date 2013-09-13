---
layout: page
title: Blog
tagline: dfchx
---

[my github] (https://github.com/danfengchaoxi)

## To-Do

<ul>
    <li>《鸟哥的Linux私房菜 基础学习篇(第三版)》</li>
    <li>《模式设计》</li>
</ul>

## Doing

<ul>
    <li>Linux是什么</li>
    <li>abstract factory</li>
</ul>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
