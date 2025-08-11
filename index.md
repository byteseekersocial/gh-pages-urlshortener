---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site.go %}
{{ s.filename }} {{ s.name }}
    <li>{{ s.url | replace 's', '' | replace: '/go/', '' }} ➡️ {{ s.goto }}</li>
{% endfor %}
</ul>
