---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site.go %}
    <li><a href="{{s.url | replace: '/go', 'go' }}">{{ s.url | replace: '.html', '' | replace: '/go/', '' }}</a></li>
{% endfor %}
</ul>
