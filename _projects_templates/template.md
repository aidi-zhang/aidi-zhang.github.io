---
layout: page
title: "Project Title"           # use quotes if title contains a colon
description: Short description   # shown on the project card
img: assets/img/your_image.jpg   # preview image for the card (optional)
importance: 1                    # lower number = shown first
category: work                   # work | fun
related_publications: key1, key2 # comma-separated keys from _bibliography/papers.bib (optional)
giscus_comments: false           # set true to enable comments
redirect:                        # set to a URL to redirect the card to an external page
---

Project description goes here.

<!-- Embed a YouTube video -->
<div style="position: relative; width: 100%; padding-top: 56.25%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    src="https://www.youtube.com/embed/VIDEO_ID"
    frameborder="0" allowfullscreen></iframe>
</div>

<!-- Embed a Google Slides presentation -->
<div style="position: relative; width: 100%; padding-top: 56.25%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    src="https://docs.google.com/presentation/d/e/YOUR_ID/embed?start=false&loop=false"
    frameborder="0" allowfullscreen></iframe>
</div>

<!-- Image grid (1/3 each) -->
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/your_image.jpg" title="caption" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
