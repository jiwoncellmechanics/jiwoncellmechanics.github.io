---
layout: single
title: "Publications (debug)"
permalink: /publications/
---

<p><strong>Total docs:</strong> {{ site.publications | size }}</p>

<ul>
{% for doc in site.publications %}
  <li>{{ doc.title }} — <code>{{ doc.path }}</code> — <a href="{{ doc.url }}">{{ doc.url }}</a></li>
{% endfor %}
</ul>
