<div class="contributors">
{% for contributor in site.github.contributors %}
[![Avatar]({{ contributor.avatar_url }}){: style="width: 30px;"}]({{ contributor.html_url }}) [@{{ contributor.login }}]({{ contributor.html_url }})
{: .contributor }
{% else %}
This project would not be possible without the help of [our amazing contributors] on GitHub.
{% endfor %}
</div>
