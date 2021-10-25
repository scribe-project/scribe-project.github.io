---
title: "News"
layout: textlay
excerpt: "SCRIBE - Machine Transcription of Norwegian Conversational Speech"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
