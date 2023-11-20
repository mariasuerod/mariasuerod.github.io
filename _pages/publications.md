---
layout: archive
title: "Working papers"
permalink: /publications/
author_profile: true
---


* Risky returns, infection levels and their role in shaping producer preferences for farm animal
health and welfare in the UK. [Draft coming soon]

* Resource Allocation: A general decision-making framework of woodland planting in the UK. [Draft coming soon]

* Disentangling farm animal health from farm animal welfare and information asymmetry: A case study on UK consumer preference.
  An older version is published as a conference paper and can be found [here](https://econpapers.repec.org/paper/agsaesc21/312057.htm)
  


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
