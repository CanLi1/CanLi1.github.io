---
title: "News"
layout: textlay
excerpt: "Li Group at Purdue University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
{% if article.url %}
<em><a href="{{ article.url }}">{{ article.headline }}</a></em></p>
{% else %}
<em>{{ article.headline }}</em></p>
{% endif %}
{% endfor %}
