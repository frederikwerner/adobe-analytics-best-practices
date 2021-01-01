---
layout: default
title: Welcome to the Adobe Analytics Best Practices Repo!
---
<h1>Welcome to the collection of best practices for Adobe Analytics!</h1>
<p>This is an open project aiming to collect and maintain an ever-growing list of best practices for Adobe Analytics. This project is hosted on [Github]({{site.github.repository_url}}). If you want to [contribute]({{site.github.issues_url}}), have a [question]({{site.github.repository_url}}/discussions), or just want to hang out with the contributers, feel free to join the repo!</p>
<p>Contributers so far:
  <ul>
    {% for contributor in site.github.contributors %}
      <li>
        <img src="{{ contributor.avatar_url }}" width="32" height="32" />
        <a href="{{ contributor.html_url }}">{{ contributor.login }} ({{ contributor.contributions }} contributions)</a>
      </li>
    {% endfor %}
  </ul>
</p>