<!-- Inject custom CSS -->
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

# Welcome to *Café, Con Amor*

Follow Andrea’s journey as she leaves behind a life of expectations to chase her dreams.

## Read the Chapters
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
