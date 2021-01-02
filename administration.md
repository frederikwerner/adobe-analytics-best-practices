---
layout: default
title: Best practices for administrating Adobe Analytics
---
# {{page.title}}
This section contains best practices around how to administrate Adobe Analytics, which settings should be adapted over time, and how to be most efficient.

List of content:
  {% assign mypages = site.html_pages | sort: "title" %}
  {% assign comparepage = page.name | remove: ".md" %}
    {% for pageitem in mypages %}
    {% assign comparedir = pageitem.dir | remove: "/" %}
    {% if comparedir == comparepage %}
* [{{ pageitem.title }}](./{{ pageitem.url}})
    {% endif %}
  {% endfor %}

[Back to Homepage]({{site.url}}/index.html)