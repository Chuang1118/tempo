---
---
{% include section.html size="full" %}
{% include banner.html image="images/Laboratorio-Banner-5-Detecta.webp" %}
{% include section.html %}


# **Signaling Microenvironment and B Lymphoid Hemopathies** 

INSERM UMRS 1349 SIMHEL is a single-team unit created in 2009 that develops a program of translational and fundamental research on CLL (chronic lymphocytic leukemia). This approach helps quickly move basic research into clinical applications: turning research into real-world treatments. The three main pillars of our research are:
- **Function of leukemic cells** Identification of functional alterations regulating BCR signaling and CLL survival thermoplastic tapes 
- **Tumor cells in their microenvironment** 
- **Transfer to the patient** 

{% capture col1 %}

{% include button-link.html 
   image_url="images/mrHvlPRY.jpeg" 
   text="Our science" 
   link="research" 
%}

{% endcapture %}
{% capture col2 %}

{% include button-link.html 
   image_url="images/mrHvlPRY.jpeg" 
   text="Our technology" 
   link="technology" 
%}


{% endcapture %}
{% capture col3 %}

{% include button-link.html 
   image_url="images/mrHvlPRY.jpeg" 
   text="Research group" 
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
The TisCel13 platform offers and develops services that enable the visualization and analysis of the structure, dynamics, interactions, and functions of normal and pathological tissues and cell populations using a variety of methodological approaches. To this end, the TisCel13 platform brings together histology and flow cytometry resources under one roof.

{%
  include button.html
  link="https://tiscel13.univ-paris13.fr/index.php"
  text="READ MORE"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
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

# {% include icon.html icon="fa-solid fa-building-columns" %}Our research unit is funded by

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
  image="images/funding/Logo-Avicenne.png"
  link="https://chu93.aphp.fr/"
  width="400px"
%}


{% endcapture %}

{%
  include grid.html
  content=content
  style="rectangle"
%}