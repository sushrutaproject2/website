---
layout: page
permalink: /publications/
title: Project publications
description: In reversed chronological order. 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid  --query @*[keyword=ssproject]* %}

<div class="publications">

{% bibliography %}

</div>
