---
layout: page
title: DATA LIVES
tagline: An attempt at creating an interface between Data and Humanity
---
{% include JB/setup %}

## Posts!

{% for post in site.posts %}
<span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

