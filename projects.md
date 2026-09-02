---
layout: page
title: "Projects"
banner_icon: fa-flag
subtitle: A small overview of running projects
background_image: images/bg_wad.jpg
permalink: "/projects.html"
---

## Ongoing projects
{: .major}

<!-- {% include feature-grid.html items=site.projects %} -->
{% assign featured_projects = site.projects | where: "featured", true | sort: "sort_order" %}
{% include feature-grid.html items=featured_projects %}
