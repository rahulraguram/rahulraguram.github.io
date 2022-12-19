---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order. Check <a href='https://scholar.google.com/citations?user=iHJLHq8AAAAJ&hl=en'>Google Scholar</a> for more details.
years: [2013, 2012, 2011, 2010, 2009, 2008, 2007]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
