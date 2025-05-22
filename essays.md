---
layout: default
title: Essays
permalink: /essays/
---

# Essays

Here’s a collection of essays reflecting experience, growth, and ideas:

<ul>
  {% for essay in site.essays %}
    <li>
      <a href="{{ essay.url }}">{{ essay.title }}</a>
      <small>({{ essay.date | date: "%B %d, %Y" }})</small>
    </li>
  {% endfor %}
</ul>