---
layout: archive
permalink: /blog/
title: Blog
author_profile: true
---

{% assign posts = site.posts %}
{% for post in posts %} 
{% include archive-single.html type="list" %} 
{% endfor %}