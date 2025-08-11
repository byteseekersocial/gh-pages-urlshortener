---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site.go %}
    <li>{{ s.url | replace: '/go/', '' | replace '.html', '' }} ➡️ {{ s.goto }}</li>
{% endfor %}
</ul>
