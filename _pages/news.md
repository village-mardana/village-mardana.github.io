---
title: "News"
layout: textlay
excerpt: "News-Mardana."
sitemap: false
permalink: /news.html
---

# News
  <div id="newsid" class="col-sm-8" >
  
{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

</div>

 <div id="newsfeed" class="col-sm-4" >
  {% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
  </div>

