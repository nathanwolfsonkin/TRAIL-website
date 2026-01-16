---
title: Contact
nav:
  order: 5
  tooltip: Email, Phone, and Address
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Temple University College of Engineering, located in Philadelphia, Pennsylvania. 
{:.center}

{%
  include button.html
  type="email"
  text="pdames@temple.edu"
  link="pdames@temple.edu"
%}
{%
  include button.html
  type="phone" 
  text="(215) 204-7974"
  link="+1-215-204-7974"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/College+of+Engineering+at+Temple+University/@39.9824908,-75.1554673,17z/data=!3m1!4b1!4m6!3m5!1s0x89c6c80a3ccc07bb:0xe07fe8f636375d6f!8m2!3d39.9824908!4d-75.152887!16s%2Fg%2F11bxvkxcgg?entry=ttu&g_ep=EgoyMDI2MDEwNy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/bell_tower.jpg"
  caption="Temple University's Iconic Bell Tower"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/sky_view.jpg"
  caption="Our Campus is Located Right in the Heart of North Philadelphia"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

