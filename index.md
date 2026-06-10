---
layout: page
title: "Index"
permalink: /index/
---

<ul class="master-blog-index">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
        <span class="index-title">{{ post.title }}</span>{% if post.subtitle %}<span class="index-paren"> (</span><span class="index-subtitle">{{ post.subtitle }}</span><span class="index-paren">)</span>{% endif %}
      </a>
    </li>
  {% endfor %}
</ul>