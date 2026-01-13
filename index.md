---
---

# ABOUT TRAIL

TRAIL seeks to enable teams of mobile robots to autonomously explore and gather information with limited a priori knowledge of the given situation, turning sensor data into actionable information. This work has immediate application to a broad range of scenarios, including infrastructure inspection, security and surveillance, mapping, environmental monitoring, precision agriculture, and search and rescue. In any of these scenarios there is uncertainty in the environment, the sensors, and the robots. Additionally, the number of objects of interest (e.g., injured persons in a first responder scenario) is often unknown, and there may be unpredictable physical phenomena. By developing mathematical tools and building systems that explicitly consider and reason about all of these sources of uncertainty, we seek to improve the performance of robotic teams in real-world applications.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
