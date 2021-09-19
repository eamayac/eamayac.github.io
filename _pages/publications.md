---
layout: archive
title: " "
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Publications
---- 

My previous job positions have involved:

* Academia: Teaching and Research Assistant at [USIL](https://investigacion.usil.edu.pe/), [PUCP](https://departamento.pucp.edu.pe/economia/)



