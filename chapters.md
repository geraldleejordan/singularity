---
layout: page
title: Chapters
---

 <ul>
 {% assign sorted_posts = (site.categories.['chapters'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ base }}{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
