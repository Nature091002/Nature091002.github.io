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
        color: rgb(0, 0, 0); /* Default color for light mode (black) */
    }

    @media (prefers-color-scheme: dark) {
        .co-first-authors {
            color: rgb(255, 255, 255); /* Color for dark mode (white) */
        }
    }
</style>
<h6><a href="https://scholar.google.com/citations?user=IlCpbvkAAAAJ&hl=ko" style="color: rgb(16,93, 215);">Link to Google Scholar</a></h6>
<h6 class="co-first-authors">+: co-first authors</h6>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
