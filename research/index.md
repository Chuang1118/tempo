---
title: Science
nav:
  order: 1
  tooltip: Ongoing and past research topics
---

{% include section.html size="full" %}
{% include banner.html image="images/laboratorio-banner-2.png" %}
{% include section.html %}


# {% include icon.html icon="fa-solid fa-microscope" %}Science
{% include section.html %}
Translational and basic research on CLL focuses on three main areas: 1) better defining genetic and functional alterations, particularly with the aim of improving patient stratification and understanding tumor progression; 2) determining the influence of the tumor microenvironment on tumor progression; 3) translational and machine learning models for integrating fundamental and clinical-biological data into preclinical research.

{% capture col1 %}

{% include list.html data="science_data" component="card" filter="group == 'featured_topic1'" %}

{%
  include button.html
  link="science_data/topics/Topic_1"
  text="READ MORE"
  icon="fas fa-arrow-right"
  flip=true
%}

{% endcapture %}
{% capture col2 %}

{% include list.html data="science_data" component="card" filter="group == 'featured_topic2'" %}

{%
  include button.html
  link="science_data/topics/Topic_2"
  text="READ MORE"
  icon="fas fa-arrow-right"
  flip=true
%}

{% endcapture %}

{% capture col3 %}

{% include list.html data="science_data" component="card" filter="group == 'featured_topic3'" %}

{%
  include button.html
  link="science_data/topics/Topic_3"
  text="READ MORE"
  icon="fas fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}

Learn more about our research. Research projects

{% include search-box.html %}

{% assign project_tags = "" | split: "" %}

{% for project in site.projects %}
  {% assign project_tags = project_tags | concat: project.tags %}
{% endfor %}

{% include tags.html tags=project_tags %}

{% include search-info.html %}

{% include section.html %}

## Ongoing projects

{% include project-list.html data="projects" component="project-excerpt" data-style="slide" filter="!end_date" glider=false%}

{% include section.html %}

## Past projects

{% include project-list.html data="projects" component="project-excerpt" filter="end_date" style="expand" glider=false%}
