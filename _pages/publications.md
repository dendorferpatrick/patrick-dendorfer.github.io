---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



{% include base_path %}

{% assign publication_ordered = site.publications | sort: 'date' | reverse %}
{% for post in publication_ordered %}
  {% include archive-single.html %}
{% endfor %}
