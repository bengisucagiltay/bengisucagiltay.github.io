---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

  You can access the full-papers and talk recordings in each publication listed below.
  
  You can also find the full list of my publications on [Google Scholar profile](https://scholar.google.com/citations?user=C8nNN80AAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
