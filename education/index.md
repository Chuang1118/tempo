---
title: Education
nav:
  order: 3
  tooltip: teaching
---

{% include section.html size="full" %}
{% include banner.html image="images/education/teaching_scaled_cropped.png" %}
{% include section.html %}

# {% include icon.html icon="fa-brands fa-font-awesome" %}Education

Knowledge transfer is one of SIMHEL's missions. 

## Teaching staff

{% include list.html data="members" component="portrait" filter="role == 'professor'" style="small" show_name=true %}

{% include list.html data="members" component="portrait" filter="role == 'associate-professor'" style="small" show_name=true %}

## Featured

{% include list.html data="education_data" component="card" filter="group == 'featured_m1'" %}

{% include section.html %}

{% capture col1 %}

{% include list.html data="education_data" component="card" filter="group == 'featured_m1'" %}

{% endcapture %}
{% capture col2 %}

{% include list.html data="education_data" component="card" filter="group == 'featured_m2'" %}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}
