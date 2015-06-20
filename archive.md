---
layout: page
title: archive
header-img: "img/rome.jpg"
permalink: pretty
---

## Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}