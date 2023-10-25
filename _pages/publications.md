---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
years: [2023]
nav: true

---
<!-- _pages/publications.md -->
<div class="publications">

{% for y in page.years %}
  <h4 class="year">{{y}}</h4>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
