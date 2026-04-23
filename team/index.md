---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

UMR1349 at Sorbonne Paris Nord University led by Dr. Nadine Varin-Blank. 

Our research combines experimental, clinical and numerical approaches, including machine learning, to study the properties of CLL and its microenvironment. We believe .... 

{% capture text %}

Dr. Nadine Varin-Blank, INSERM Research Director is heading the INSERM 1349 Unit / SIMHEL Laboratory  (Signaling, microenvironment and B cell malignancies) UFR SMBH at University Sorbonne Paris Nord (USPN). The unit is composed of tenure scientists from Inserm, USPN University and Public hospital (Avicenne, APHP) (PhD, MD-PhD, Engineers and technical assistants) as well as doctoral and postdoctoral fellows. The major topic of the Unit is to characterize the key dysfunctional mechanisms responsible for the pathophysiology of chronic lymphoid neoplasms.


{%
  include button.html
  link="/members/nadine-varin-blank"
  text="Learn More"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team/nadine-varin-blank_scaled.jpg"
  title="Dr. Nadine Varin-Blank"
  component="portrait"
  text=text
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'professor'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'pu-ph'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'ro'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'research-engineer'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'associate-professor'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" show_name=true %}

{% include list.html data="members" component="portrait" filter="role == 'ra'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'programmer'" show_name=true %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" show_name=true %}


{% include section.html background="images/banner.png" dark=true %}
Our mission is to bridge fundamental research to bed-side. 

We actively welcome fresh ideas and novel perspectives and are committed to training the next generation of researchers. Learn more about our open positions and available MSc thesis projects.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join us!" link="opportunities" style="button" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" style="small" show_name=true %}

