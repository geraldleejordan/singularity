---
layout: page
title: Bibliography
---

 <ul>
 {% assign sorted_posts = (site.categories.['bibliography'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
