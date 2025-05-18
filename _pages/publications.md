---
layout: page
title: Publications
permalink: /publications/
nav: true
nav_order: 3
---

<!-- Search bar for filtering publications -->
{% include bib_search.liquid %}

<!-- Publication list with bullets -->
<div class="publications">

    {% bibliography --template bib-custom %}

</div>