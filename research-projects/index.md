---
title: Projects
nav:
  order: 2
  tooltip: Our Current Research Projects
---

# {% include icon.html icon="fa-solid fa-users" %}Projects

{% capture text %}

The ability to track, predict and reason about pedestrians and vehicles in a fast-paced dense urban environment is crucial to ensuring that autonomous vehicles can operate safely and dependably. This project focuses on providing that capability to fleets of autonomous cars and delivery drones, allowing these autonomous systems to realize their promised societal benefits, such as the potential for greater mobility of people and goods while reducing traffic congestion and increasing safety. This technology can moreover be customized for other applications such as large manufacturing operations and even small household robotic applications.

{%
  include button.html
  link="research-projects/distributed-tracking.html"
  text="Learn More"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/index/research.jpg"
  link="research-projects/distributed-tracking.html"
  title="Distributed Tracking"
  text=text
%}

{% capture text %}

Stay up to date on the latest from TRAIL
{:.center}

{%
  include button.html
  link="blog"
  text="Check out our blog"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/index/blog.jpg"
  link="projects"
  title="Our Blog"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a diverse group of graduate students, undergraduate researchers, and collaborators united by a shared interest in robotics, autonomy, and artificial intelligence. Learn about our members here

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
