---
layout: default
title: Homepage
---
# Welcome to the collection of best practices for Adobe Analytics!
This is an open project aiming to collect and maintain an ever-growing list of best practices for Adobe Analytics. This project is hosted on [Github]({{site.github.repository_url}}). If you want to [contribute]({{site.github.issues_url}}), have a [question]({{site.github.repository_url}}), or just want to hang out with the contributors, feel free to join the repo!

Existing topics:
* [Implementation](./implementation.html)
* [Administration](./administration.html)
* [Usage](./usage.html)
* [Training & Enablement](./training.html)

Contributors so far:
    {% for contributor in site.github.contributors %}
* <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" />{{ contributor.login }} ({{ contributor.contributions }} contributions)</a>
    {% endfor %}