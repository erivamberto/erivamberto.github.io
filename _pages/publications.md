---
layout: page
permalink: /publications/
title: publications
description: research articles, submitted preprints, and other bibliographic productions.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[status!=submitted && type!=phdthesis && type!=mastersthesis] %}

</div>

## submitted papers

<div class="publications">

{% bibliography --query @*[status=submitted] %}

</div>

## theses and dissertations

<div class="publications">

{% bibliography --query @phdthesis, @mastersthesis %}

</div>
