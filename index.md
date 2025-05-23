---
layout: default
---

<h1>مرحبًا بكم في مدونتي</h1>

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
