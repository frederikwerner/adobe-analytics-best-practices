---
layout: default
title: Welcome to the Adobe Analytics Best Practices Repo!
---
<ul>
{% for contributor in site.github.contributors %}
  <li>
    <img src="{{ contributor.avatar_url }}" width="32" height="32" />
    <a href="{{ contributor.html_url }}">{{ contributor.login }} ({{ contributor.contributions }} contributions)</a>
  </li>
{% endfor %}
</ul>
