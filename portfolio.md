---
layout: default
title: Portfolio
permalink: /portfolio/
date:   2015-01-15 09:00:00
---

{% assign portfolio_intro = "These are just a few of the projects I have worked on in the last few years. There are loads more, mainly smaller stuff. These are just the ones that I thought it was worth writing about." %}

{% assign posts = site.categories.portfolio %}
{% include portfolio.html %}