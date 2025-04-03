---
layout: home
title: Welcome to Fuse
---

# Welcome to Fuse

A Project 1999 Guild

## Latest Updates

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%B %-d, %Y" }}
{{ post.excerpt }}
{% endfor %}

