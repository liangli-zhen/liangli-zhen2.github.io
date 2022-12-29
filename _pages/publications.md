---
layout: page
permalink: /publications/
title: publications
description: The asterisk symbol (*) denotes the corresponding author. <a href='https://scholar.google.com/citations?user=dtv_LZkAAAAJ&hl=en' target='_blank'><strong>Google Scholar Profile</strong></a>
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2014, 2013]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
<br><br>


&#169; The copyright of the papers above is owned by the respective publishers. The electronic versions here are made available under the <a href='http://creativecommons.org/licenses/by-nc-nd/4.0/'>CC-BY-NC-ND 4.0 license</a>.
