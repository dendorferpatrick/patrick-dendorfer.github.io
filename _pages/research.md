---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---





{% include base_path %}

{% assign research_ordered = site.research | sort: 'date' | reverse %}
{% for post in research_ordered %}
{% include archive-single-research.html %}
{% endfor %}
