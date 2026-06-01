---
---
{% include section.html size="full" %}
{% include banner.html image="images/Laboratorio-Banner-5-Detecta.webp" %}
{% include section.html %}


# **Signaling Microenvironment and B Lymphoid Hemopathies**

**Since 2009, INSERM UMR 1349 SIMHEL develops a translational program on chronic B lymphoid neoplasms, focusing on chronic lymphocytic leukemia and mantle cell lymphoma. Our strategy involves combining fundamental and clinically oriented approaches on signaling mechanisms involved in disease progression. Our aim is to translate our knowledge to the stratification of patients and to new therapeutic options.**

{% capture col1 %}

{% include button-link.html 
   image_url="images/letterS.png" 
   text="our **S**cience" 
   link="research" 
%}

{% endcapture %}
{% capture col2 %}

{% include button-link.html 
   image_url="images/letterT.png" 
   text="our **T**echnology" 
   link="technology" 
%}


{% endcapture %}
{% capture col3 %}

{% include button-link.html 
   image_url="images/letterG.png" 
   text="research **G**roup" 
   link="team" 
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}

{% include section.html %}

{% capture col1 %}
{%
  include figure.html
  image="images/Call_CPJ.png"
  width="800px"
%}

{% endcapture %}
{% capture col2 %}

## <span style="color:#354878">**Call for applicants for the Inserm chair in cancer research**</span>

<span style="color:#8b7d6d">**INSERM invites applications from junior profossorship who wish to manage and lead research teams and participate in national, European or international projects. The position is offered on a fixed-term contract with a view to tenure in the Inserm Research Director personnel at the end of the contract.**</span>
{%
  include button.html
  link="opportunities"
  text="READ MORE"
  icon="fas fa-arrow-right"
  flip=true
%}

{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

{% include section.html %}

{% capture col1 %}
{%
  include figure.html
  image="images/eric.jpg"
  width="800px"
%}

{% endcapture %}
{% capture col2 %}

## <span style="color:#354878">**Signaling targets in search of societal impact**</span>

<span style="color:#8b7d6d">**Beyond translating basic science into European guidelines, our work adds societal value through our knowledge on signaling target, specifically targeting the gap between what guidelines recommend ("ideal practice") and what happens in the clinic ("realistic best practice").**</span>

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
%}




{% include section.html %}

{% capture col1 %}

<div style="max-width:600px;">
  <iframe width="100%" height="400"
    src="https://www.youtube.com/embed/2-rYeWkrLvY"
    title="YouTube video"
    frameborder="0"
    allowfullscreen>
  </iframe>
</div>

{% endcapture %}
{% capture col2 %}
<br/>
### <span style="color:#8b7d6d">**"Meaningful research begins with motivation, and failures guide us toward improvement."**</span>
<br/>
<br/>
<span style="color:#354878">Dominique Ledoux</span>

<span style="color:#354878">**Professor of Molecular Biology at Sorbonne Paris-Nord University /  Vice president for research at the university (2014–2016) / Director of the university’s doctoral school “Sciences, Technologies, Santé-Galilée” (2016–2020)**</span>
{% endcapture %}


{%
  include cols.html
  col1=col1
  col2=col2
%}



{% include section.html %}

## Highlights

<div class="glider-container">
  <div class="glide">
    <div class="glide__track" data-glide-el="track">
      <div class="glide__slides">
        {% include project-list.html data="projects" component="project-excerpt" glider=true style="slide" filter="!end_date"%}
      </div>
    </div>
    <div class="glide__arrows" data-glide-el="controls">
      <button class="glide__arrow glide__arrow--left" data-glide-dir="<">{% include icon.html icon="fa-solid fa-arrow-left" %}</button>
      <button class="glide__arrow glide__arrow--right" data-glide-dir=">">{% include icon.html icon="fa-solid fa-arrow-right" %}</button>
    </div>
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/@glidejs/glide"></script>
<script>
  const glide = new Glide('.glide', {
    type: "carousel",
    perView: 2,
    breakpoints: {
      600: { perView: 1 },
      1200: { perView: 2 }
    },
    autoplay: 2000,
    hoverpause: true,
    focusAt: "center"
  }).mount()
</script>

{% include section.html %}
{% capture content %}

{%
  include figure.html
  image="images/funding/logo_inserm.png"
  link="https://www.inserm.fr/"
  width="400px"
%}

{%
  include figure.html
  image="images/funding/LOGOTYPE Officiel - Universite݁ Sorbonne Paris Nord.png"
  link="https://www.univ-spn.fr/"
  width="400px"
%}

{%
  include figure.html
  image="images/funding/Logo-Avicenne_new.jpg"
  link="https://chu93.aphp.fr/"
  width="260px"
%}


{% endcapture %}

{%
  include grid.html
  content=content
  style="rectangle"
%}