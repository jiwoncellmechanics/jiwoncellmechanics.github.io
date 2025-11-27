---
layout: single
title: "Publications"
collection: publications
entries_layout: grid
show_excerpts: true
show_teasers: true
permalink: /publications/
---
<ul class="pub-list">
  {% for post in site.publications %}
  <li class="pub-item">
    <div class="pub-image">
      {% if post.header.teaser %}
        <img src="{{ post.header.teaser | relative_url }}">
      {% endif %}
    </div>

    <div class="pub-text">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </div>
  </li>
  {% endfor %}
</ul>
