---
layout: default
---

<h3>Welcome to my Blog</h3>

<div>
  {% for post in site.posts %}
    <ul>
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    </ul>
  {% endfor %}
</div>