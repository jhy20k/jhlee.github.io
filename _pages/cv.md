---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 2
description: Curriculum Vitae of Junghyeok Lee.
---

<style>
.cv-pdf-container {
  width: 100%;
  height: 85vh;
  border: 1px solid var(--global-divider-color);
  border-radius: 12px;
  overflow: hidden;
  background: var(--global-bg-color);
}

.cv-pdf-container iframe {
  width: 100%;
  height: 100%;
  border: none;
}

.cv-download {
  margin-top: 1rem;
  text-align: right;
}
</style>

<div class="cv-pdf-container">
  <iframe
    src="{{ '/assets/pdf/CV_Junghyeok_Lee_2026_07.pdf' | relative_url }}#toolbar=1&navpanes=0&scrollbar=1"
    title="Junghyeok Lee CV">
  </iframe>
</div>

<div class="cv-download">
  <a href="{{ '/assets/pdf/CV_Junghyeok_Lee_2026_07.pdf' | relative_url }}" target="_blank">
    Download CV PDF
  </a>
</div>
