---
layout: archive
title: "Working papers"
permalink: /publications/
author_profile: true
---


Risky returns, infection levels and their role in shaping producer preferences for farm animal
health and welfare in the UK. [Draft coming soon]
<br>
Resource Allocation: A general decision-making framework of woodland planting in the UK. [Draft coming soon]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
