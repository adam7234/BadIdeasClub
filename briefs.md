---
layout: default
title: Briefs
permalink: /briefs/
---

# Briefs

<ul>
  {% for b in site.briefs reversed %}
    <li><a href="{{ b.url | relative_url }}">{{ b.title }}</a> — {{ b.date | date: "%b %-d, %Y" }}</li>
  {% endfor %}
</ul>
