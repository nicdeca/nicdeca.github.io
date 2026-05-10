---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

See [Google Scholar](https://scholar.google.com/citations?user=UqoXixwAAAAJ&hl=it&oi=ao) for a complete list.

<div class="publications">

<h2>Recent Articles under Review</h2>
{% bibliography -q @misc %}

<h2>Journal Papers</h2>
{% bibliography -q @article %}

<h2>Conference Papers</h2>
{% bibliography -q @inproceedings %}

<h2>PhD thesis</h2>
{% bibliography -q @phdthesis %}

</div>
