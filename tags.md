---
layout: default
title: 標籤
---
<h2>標籤</h2>
<ul>
{% assign all_tags = site.tags | sort %}
{% for tag in all_tags %}
  <li>
    <a href="#{{ tag[0] }}">#{{ tag[0] }}</a>（{{ tag[1].size }}）
  </li>
{% endfor %}
</ul>

<hr>

{% for tag in all_tags %}
  <h3 id="{{ tag[0] }}">#{{ tag[0] }}</h3>
  <ul>
  {% for post in tag[1] %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> · {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
  </ul>
{% endfor %}
