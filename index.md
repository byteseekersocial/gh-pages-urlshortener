---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site. %}
    <li><a href="{{s.url | replace: '/', '' }}">{{ s.url | replace: '.html', '' | replace: '/', '' }}</a></li>
{% endfor %}
</ul>
