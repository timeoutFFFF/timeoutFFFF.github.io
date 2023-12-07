---
title:  "Blogs"
layout: archive
permalink: /blogs/
author_profile: true
comments: false
---


<ul>
{% for post in site.posts %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<p>{{ post.content | strip_html | truncatewords: 40 }}</p>
{% endfor %}
</ul>
