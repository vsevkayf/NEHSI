---
layout: page
title: Media
permalink: /media/
---

<ul class="listing">
{% for reportage in site.articles %}
  {% capture y %}{{reportage.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ reportage.date | date:"%Y-%m-%d" }}">{{ reportage.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ site.baseurl }}{{ reportage.url }}" title="{{ reportage.title }}">{{ reportage.title }}</a>
  </li>
{% endfor %}
</ul>
