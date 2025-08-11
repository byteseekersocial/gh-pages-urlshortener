---
title: all shorturls
layout: index
---
<h1>All redirects</h1>
<ul>
{% for s in site.go %}
    <li><a href="{{s.url | replace: '/go', 'go' }}">{{ s.url | replace: '.html', '' | replace: '/go/', '' }}</a> ➡️ <a href="{{ s.goto }}">{{ s.goto }}</a></li>
{% endfor %}
</ul>

<footer>
<p></p>
<p><a href="https://codepo8.github.io/gh-pages-urlshortener/">GH pages urlshortener</a> by <a href="https://christianheilmann.com">Chris Heilmann</a></p>
</footer>