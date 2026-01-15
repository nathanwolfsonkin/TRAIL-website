---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group != 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

PhD Alumni
{:.center}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'alum' && role == 'phd'" %}

{% include section.html background="images/background.jpg" dark=true %}

Undergraduate and Masters Alumni
{:.center}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group == 'alum' && role != 'phd'" %}