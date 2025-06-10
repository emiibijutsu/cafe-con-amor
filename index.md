---
layout: default
title: Home
---

# ☕ Welcome to *Café, Con Amor*

Follow Andrea’s journey as she leaves behind a life of expectations to chase her dreams.

## 📚 Read the Chapters
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
