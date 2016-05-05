---
layout: page
title: Media
permalink: /media/
---

Environmental Health and Sustainability News:

<ul class="listing">
{% for post in site.posts %}
  {% if post.categories contains 'Media' %}
    {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
    {% if year != y %}
      {% assign year = y %}
      <li class="listing-seperator">{{ y }}</li>
    {% endif %}
    <li class="listing-item">
      <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
      <a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>

Recommended Articles:  

Krasnov, H., Katra, I., Koutrakis, P., Friger, M. (2014) Contribution of dust storms to PM10 levels in an urban arid environment. Journal of the Air & Waste Management Association 64, 89-94.  

Vodonos, A., Friger, M., Katra, I., Avnon, L., Krasnov, H., Koutrakis, P., Schwartz, J., Lior, O., Novack, V. (2014) The impact of desert dust exposure on hospitalization due to the exacerbation of chronic obstructive pulmonary disease. Air Quality, Atmosphere and Health. DOI 10.1007/s11869-014-0253-z.  

Yitshak-Sade, M., Novack, V., Katra, I., Gorodischer, R., Tal, A., Novack, L. (2014) Non-anthropogenic dust exposure and asthma medications purchase in children. European Respiratory Journal. DOI:10.1183/09031936.00078614  

Katra, I., Arotsker, L., Krasnov, H., Zaritski, A., Kushmaro, A., Ben-Dov, A. (2014) Richness and diversity in dust stormborne biomes at the Southeast Mediterranean.  Scientific Reports 4, 5265; DOI:10.1038/srep05265  

Yitshak-Sade, M., Vodonos, A., Novack, V., Friger, M., Ami, G., Katra, I., Schwartz, J., Novack, L. (2014) Can air pollution trigger an onset of atrial fibrillation: a population based study. Air Quality, Atmosphere and Health. DOI 10.1007/s11869-014-0295-2  

Krasnov, H., Katra, I., Novack, V., Vodonos, A., Friger, M. (2015) Increased indoor PM concentrations controlled by atmospheric dust events and urban factors. Building and Environment. doi: 10.1016/j.buildenv.2015.01.035  

Yitshak-Sade, M., Kloog, I., Liberty, I.F., Katra, I., Novack, L., Novack, V. (2015) Air pollution and serum glucose levels: a population based study. Medicine 94, e1093.  

Krasnov, H., Katra, I., Friger, M. (2015) Insights into indoor/outdoor PM concentration ratios due to dust storms in an arid region. Atmosphere 6, 879-890.  

Vodonos, A., Friger, M., Katra, I., Krasnov, H., Zager, D., Schwartz, J., Novack, V. (2015) Individual effect modifiers of dust exposure effect on cardiovascular morbidity. Plos One DOI: 10.1371/journal.pone.0137714  

Krasnov, H., Katra, I., Friger, M. (2016) Increase in dust storm related PM10 concentrations: A time series analysis of 2001-2015. Environmental Pollution 213, 36-42.  

Katra, I., Elperin, T., Fominykh, A., Krasovitov, B., Yizhaq, H. (2016) Modeling of particulate matter transport in atmospheric boundary layer following dust emission from source areas. Aeolian Research 20, 147-156.
