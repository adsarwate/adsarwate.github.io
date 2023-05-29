---
layout: page
permalink: /publications/
title: publications
description: publications of Anand D. Sarwate
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">	

<h2>Preprints</h2>

<p><b>NB:</b> ArXiv versions of published conference papers are linked from the conference paper.</p>

{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @techreport[year={{y}}]* %}
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

<h2>Book Chapters</h2>
{%- for y in page.years %}
		{% bibliography -f {{ site.scholar.bibliography }} -q @inbook[year={{y}}]* %}
{% endfor %}

<h2>Theses</h2>

{% bibliography -f {{ site.scholar.bibliography }} -q @phdthesis[year=2008]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @mastersthesis[year=2005]* %}

{% bibliography -f {{ site.scholar.bibliography }} -q @article[year=2002]* %}

</div>
