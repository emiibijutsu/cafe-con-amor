<!-- Inject custom CSS -->
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<!-- Logo -->
<p style="text-align: center;">
  <img src="{{ '/assets/img/logo.png' | relative_url }}" style="max-width: 400px;">
</p>

# Welcome to *Café, Con Amor*
#### Slice-of-Life & Romance Web Series written by Emiibijutsu

After walking away from law school — and the life her parents demanded — Andrea opens a small café in the East Village. It’s not what they imagined, but it’s hers. Between café con leches and familiar faces, she begins rebuilding a life filled with passion, healing, and unexpected connection — including a certain sleepy-eyed EMT who keeps showing up for more than just coffee. A story about finding freedom, and love — one cup at a time.

## Read the Chapters
### Season 1: Slowly Brewing
<ul>
  {% for chapter in site.chapters %}
    <li><a href="{{ chapter.url }}">{{ chapter.title }}</a></li>
  {% endfor %}
</ul>
