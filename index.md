---
layout: page
title: DATA LIVES
tagline: An attempt at creating an interface between Data and Humanity
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Sample Posts

Here's a sample "posts list".

{% for post in site.posts %}
<span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/dbtek/jekyll-bootstrap-3)!


