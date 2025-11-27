---
layout: collection
title: "Publications"
collection: publications
permalink: /publications/
classes: wide
---

{% assign pubs = site.publications | sort: "date" | reverse %}

<ul class="pub-list">
  {% for post in pubs %}
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
