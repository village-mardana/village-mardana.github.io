---
title: "RAA @ IITi - Objectives"
layout: gridlay
excerpt: "RAA @IITi -- Objectives."
sitemap: false
permalink: /objectives/
---


# Objectives and Plan of action
Jump to [Objectives](#objectives), [Plan of Action](#planning)

## Objectives

{% assign number_printed = 0 %}
{% for publi in site.data.objlist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-12 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

<hr>

# Planning
Jump back to [Objectives](#objectives)
## Plan of action

{% for publi in site.data.objlist %}
{% if publi.highlight == 0 %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}
