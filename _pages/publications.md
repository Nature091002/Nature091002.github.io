---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<style>
    .co-first-authors {
        color: rgb(255, 255, 255); /* Default color for dark mode (white) */
    }

    @media (prefers-color-scheme: light) {
        .co-first-authors {
            color: rgb(0, 0, 0); /* Color for light mode (black) */
        }
    }
</style>
<h6><a href="https://scholar.google.com/citations?user=IlCpbvkAAAAJ&hl=ko" style="color: rgb(16,93, 215);">Link to Google Scholar</a></h6>
<h6><a href="https://orcid.org/0009-0000-1533-1716" style="color: rgb(195,215, 16);">Link to ORCID</a></h6>
<h6 class="co-first-authors">+: co-first authors</h6>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
