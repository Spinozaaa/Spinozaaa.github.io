<!-- ---
layout: page
permalink: /publications/
title: publications
description: Please refer to my Google Scholar for a complete publication list.
years: [2022, 2023]
nav: true
nav_order: 1
---
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
 -->