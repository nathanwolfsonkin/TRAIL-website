---
title: Projects
nav:
  order: 2
  tooltip: Our Current Research Projects
---

# {% include icon.html icon="fa-solid fa-users" %}Projects

<div style="text-align: center; margin-bottom: 2rem;">
  <img src="/images/projects/research-projects-overview.png" style="max-width: 70%; height: auto;">
</div>

Our current research exists at the intersection of three broad areas of research: Multi-Agent Systems, Autonomy, and Real-World Applications. See how our current projects are taking on these challenges below!

{%- for project in site.research-projects -%}
  {%- assign flip_bool = forloop.index0 | modulo: 2 -%}
  {%- if flip_bool == 1 -%}
    {%- assign flip = true -%}
  {%- else -%}
    {%- assign flip = false -%}
  {%- endif -%}

  {% capture text %}

  {{ project.summary }}

  {%
    include button.html
    link=project.url
    text="Learn More"
    icon="fa-solid fa-arrow-right"
    flip=flip
    style="bare"
  %}

  {% endcapture %}

  {%
    include feature.html
    image=project.image
    link=project.url
    title=project.title
    text=text
    flip=flip
  %}

{%- endfor -%}
