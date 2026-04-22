---
title: Publications
nav:
  order: 5
  tooltip: Published works
---

{% include section.html size="full" %}
{% include banner.html image="images/pub.png" %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-bookmark" %}Publications

{% include section.html %}

## Selected Publications

{% include list.html data="citations" component="citation" style="rich" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include search-box.html %}

{% assign citation_tags = "" | split: "" %}

{% for citation in site.citations %}
  {% assign citation_tags = citation_tags | concat: citation.tags %}
{% endfor %}

{% include tags.html tags=citation_tags %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" filter="group != 'featured' and date >= '2020-01-01' and ! title.downcase.include?('conference') and ! title.downcase.include?('proceeding') and ! publisher.downcase.include?('conference') and ! publisher.downcase.include?('proceeding')" %}