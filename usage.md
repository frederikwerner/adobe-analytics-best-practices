---
layout: default
title: Best practices for using Adobe Analytics
---
# {{page.title}}
This section contains best practices around how best use Adobe Analytics from a reporting perspective.

List of content:
  {% assign mypages = site.html_pages | sort: "title" %}
  {% assign comparepage = page.name | remove: ".md" %}
    {% for pageitem in mypages %}
    {% assign comparedir = pageitem.dir | remove: "/" %}
    {% if comparedir == comparepage %}
* [{{ pageitem.title }}](./{{ pageitem.url}})
    {% endif %}
  {% endfor %}

[Back to homepage](./index.html)