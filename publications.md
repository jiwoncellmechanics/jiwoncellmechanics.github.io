---
layout: collection
title: "Publications"
collection: publications
entries_layout: grid
permalink: /publications/
author_profile: true
sort_by: date
sort_order: reverse
---

<!-- DEBUG: 컬렉션에 뭐가 들어왔는지 출력 -->
<p><strong>Total docs:</strong> {{ site.publications | size }}</p>
<ul>
{% for doc in site.publications %}
  <li>{{ doc.title }} — <code>{{ doc.path }}</code> — <a href="{{ doc.url }}">{{ doc.url }}</a></li>
{% endfor %}
</ul>
