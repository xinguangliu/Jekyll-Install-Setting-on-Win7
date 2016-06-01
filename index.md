---
layout: default
title: Xinguang Liu
---

<h2>{{ page.title }}'s Homepage</h2>

<p>最新文章</p>

<ul>
　　　　{% for post in site.posts %}
　　　　　　<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
　　　　{% endfor %}

</ul>
