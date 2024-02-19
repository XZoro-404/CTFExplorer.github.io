---
layout: default
title: Pico CTF Posts
---

<!-- Loop through all posts in the _posts/pico-ctf directory -->
{% for post in site.posts %}
{% if post.categories contains 'pico-ctf' %}
<h2>{{ post.title }}</h2>
<p>{{ post.date | date: "%B %d, %Y" }}</p>
<p>{{ post.excerpt }}</p>
<a href="{{ post.url }}">Read more</a>
<hr>
{% endif %}
{% endfor %}
