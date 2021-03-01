---
title: "News"
layout: textlay
excerpt: "Desarkar NLP Lab at IIT Hyderabad."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
