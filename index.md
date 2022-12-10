---
layout: default
---

{% for post in site.posts %}   
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <small><strong>{{ post.date | date: "%B %e, %Y" }}</strong>
  <p>{{ post.excerpt }}</p>


{% endfor %}
