---
layout: page
permalink: /publications/
title: 发表论文
description: 按类别和时间倒序排列，由 jekyll-scholar 自动生成。
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
