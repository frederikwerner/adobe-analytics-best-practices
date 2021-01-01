---
layout: default
title: Homepage
---
# Welcome to the collection of best practices for Adobe Analytics!
<p>This is an open project aiming to collect and maintain an ever-growing list of best practices for Adobe Analytics. This project is hosted on <a href="{{site.github.repository_url}}">Github</a>. If you want to <a href="{{site.github.issues_url}}">contribute</a>, have a <a href="{{site.github.repository_url}}/discussions">question</a>, or just want to hang out with the contributors, feel free to join the repo!</p>
<p>Existing topics:
* [Implementation](/implementation.html)
* [Administration](./administration.html)
* [Usage](./usage.html)
* [Training & Enablement](./training.html)
</p>
<p>Contributors so far:
  <ul>
    {% for contributor in site.github.contributors %}
      <li>
        <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" />{{ contributor.login }} ({{ contributor.contributions }} contributions)</a>
      </li>
    {% endfor %}
  </ul>
</p>