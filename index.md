---
layout: page
title: Arms Dealer
tagline: research and lecture notes
---
{% include JB/setup %}

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li>&raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> <span>{{ post.date | date_to_string }}</span> </li>
  {% endfor %}
</ul>




