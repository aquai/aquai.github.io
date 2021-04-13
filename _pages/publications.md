---
layout: page
permalink: /publications/
title: publications
years: [2021, 2020, 2019, 2018]
description: A update-to-date list of my publication can be found in my <a href="https://scholar.google.com/citations?user=wt7-UUYAAAAJ&hl=en"><u>Google Scholar</u></a> page.
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
