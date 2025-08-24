---
layout: cv
permalink: /cv/
title: cv
nav: true
nav_order: 5
cv_pdf: assets/pdf/CV.pdf   # this shows the top button
toc:
  sidebar: left
---

{% assign cv_url = 'assets/pdf/CV.pdf' | relative_url %}
<div style="aspect-ratio: 1 / 1; min-height: 80vh;">
  <iframe
    src="{{ cv_url }}"
    width="100%"
    height="100%"
    style="border:0"
    loading="lazy"
  ></iframe>
</div>

<p class="mt-3">
  <a href="{{ cv_url }}" target="_blank" rel="noopener">Open CV in new tab</a>
</p>
