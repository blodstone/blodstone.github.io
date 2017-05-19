---
layout: page
title: Hi There!
---
{% include JB/setup %}

![Profile Photo]({{ site.url }}/assets/imgs/profile.jpg){:style="float: right;margin-right: 7px;margin-top: 7px;"}

# Welcome to my blog.

This blog is intended as the place where I try to explain things that I have learn through my PhD as easy as possible to the reader. 

I hope you enjoy it.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



