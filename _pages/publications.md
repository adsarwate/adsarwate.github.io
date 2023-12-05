---
layout: page
permalink: /publications/
title: publications
description: publications of Anand D. Sarwate
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">	

{% bibliography --template bib --group_by type,year --group_order ascending,descending %}


<h2>Theses</h2>

{% bibliography -f {{ site.scholar.bibliography }} -q @phdthesis[year=2008]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @mastersthesis[year=2005]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @article[year=2002]* %}

</div>
