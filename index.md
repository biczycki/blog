---
layout: home
title: "aid4hate..."
---

<ul>
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
