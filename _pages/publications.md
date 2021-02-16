---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
published: true
---
  You can also find my articles on <u><a href="{{https://scholar.google.co.uk/citations?user=a7UuJD8AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
