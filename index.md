---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site.go %}
    <li>{{ s.url }} -> {{ s.goto }}</li>
{% endfor %}
</ul>
