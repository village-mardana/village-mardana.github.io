---
title: "News"
layout: textlay
excerpt: "News-Mardana."
sitemap: false
permalink: /news.html
---

# News


 <div id="newsfeed" class="col-sm-5" >
  <div class="fb-page" data-href="https://www.facebook.com/VillageMardana/" data-tabs="timeline" data-width="" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"><blockquote cite="https://www.facebook.com/VillageMardana/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/VillageMardana/">Mardana, Madhya Pradesh</a></blockquote></div>
  
  
  
  <div class="fb-page" data-href="https://www.facebook.com/VillageMardana/" data-tabs="timeline" data-width="" data-height="" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="true"><blockquote cite="https://www.facebook.com/VillageMardana/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/VillageMardana/">Mardana, Madhya Pradesh</a></blockquote></div>
  
  
  </div>


  <div id="newsid" class="col-sm-5" >
  
{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

</div>

