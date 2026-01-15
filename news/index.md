---
title: News
nav:
  order: 4
  tooltip: Announcements
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

<!-- Sample Text to introduce news posts -->

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
