---
layout: pageHE
title: בלוג
language: he
permalink: /he/blog/
---

בהקמה.
Example post:

<ul class="listing">
{% for postHE in site.posts %}
  {% if postHE.categories contains 'blogHE' %}
    {% capture y %}{{postHE.date | date:"%Y"}}{% endcapture %}
    {% if year != y %}
      {% assign year = y %}
      <li class="listing-seperator">{{ y }}</li>
    {% endif %}
    <li class="listing-item">
      <time datetime="{{ postHE.date | date:"%Y-%m-%d" }}">{{ postHE.date | date:"%Y-%m-%d" }}</time>
      <a href="{{ site.baseurl }}{{ post.url }}" title="{{ postHE.title }}">{{ postHE.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
