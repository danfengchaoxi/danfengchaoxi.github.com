---
layout: page
title: Blog
tagline: dfchx
---
{% include JB/setup %}

[my github] (https://github.com/danfengchaoxi)

## To-Do

####《鸟哥的Linux私房菜 基础学习篇(第三版)》

####《模式设计》

## Doing

<ul>
    <li>Linux是什么</li>
    <li>abstract factory</li>
</ul>



This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
