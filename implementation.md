---
layout: default
title: Best practices for implementing Adobe Analytics
---
# {{page.title}}
This section contains best practices around how to implement Adobe Analytics, how to plan an implementation, and how to realize business requirements.

List of content:
  {% assign mypages = site.html_pages | sort: "title" %}
  {% assign comparepage = page.name | remove: ".md" %}
    {% for pageitem in mypages %}
    {% assign comparedir = pageitem.dir | remove: "/" %}
* {{ pageitem.url}}|{{ pageitem.title }}|{{ pageitem.path }}|{{ pageitem.dir }}|{{ pageitem.name }}|{{ page.name | remove: ".md"}}|{{ pageitem.dir | remove: "/"}}
{% if comparedir == comparepage %}
  Same
{% endif %}
    {% endfor %}

[Back to homepage](./index.html)