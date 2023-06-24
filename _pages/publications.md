---
layout: page
permalink: /publications/
title: Publications
description: Full publications on <a href=https://scholar.google.com/citations?user=AgqvtZkAAAAJ&hl  style=color:#389AC4>Google Scholar.</a><br> &#42; inidicates equal contribution.
years: [2023, 2022]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
