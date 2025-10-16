---
layout: default
title: 歸檔
---
<h2>依年份</h2>
{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h3>{{ year.name }}</h3>
  <ul>
    {% for post in year.items %}
      <li>{{ post.date | date: "%m-%d" }} · <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
