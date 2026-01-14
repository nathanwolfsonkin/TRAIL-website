---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'alumni' && role != 'phd-alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

PhD Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'phd-alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

Undergraduate and Masters Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}