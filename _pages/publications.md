---
layout: archive
title: "Publications"
permalink: /publications/
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
author_profile: true
---

#### Full Publication List
[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)

<!-- 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>

<sup>*</sup> Corresponding authorship
