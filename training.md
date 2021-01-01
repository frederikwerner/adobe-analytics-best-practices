---
layout: default
title: Best practices for training and enabling users on Adobe Analytics
---
# {{page.title}}
This section contains best practices around how to train users on Adobe Analytics and how to cater for self-service.

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