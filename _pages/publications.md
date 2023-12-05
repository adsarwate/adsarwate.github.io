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

<h2>Preprints</h2>

<p><b>NB:</b> ArXiV versions of published conference papers are linked from the conference paper.</p>

{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @techreport[year={{y}}]* %}
{% endfor %}

<h2>Book Chapters</h2>
{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @inbook[year={{y}}]* %}
{% endfor %}

<h2>Journal Papers</h2>
{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @article[year={{y}}]* %}
{% endfor %}

<h2>Conference Papers</h2>
{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @incollection[year={{y}}]* %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @inproceedings[year={{y}}]* %}
{% endfor %}	


<h2>Theses</h2>

{% bibliography -f {{ site.scholar.bibliography }} -q @phdthesis[year=2008]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @mastersthesis[year=2005]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @article[year=2002]* %}

</div>
