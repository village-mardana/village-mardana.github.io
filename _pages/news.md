---
title: "News"
layout: textlay
excerpt: "News-Mardana."
sitemap: false
permalink: /news.html
---

# News
[Loading....]

 <div id="newsfeed" class="" >
  <div class="fb-page" data-href="https://www.facebook.com/VillageMardana/" data-tabs="timeline,events" data-width="" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"><blockquote cite="https://www.facebook.com/VillageMardana/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/VillageMardana/">Mardana, Madhya Pradesh</a></blockquote></div>
  
</br>
</br>
<div id="newsid" class="" >
  
{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

</div>

