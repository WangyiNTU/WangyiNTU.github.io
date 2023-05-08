---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

#### Full Publication List
[Google scholar](https://scholar.google.com.sg/citations?user=MAG909MAAAAJ&hl=en)

<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


<sup>*</sup> Corresponding authorship
