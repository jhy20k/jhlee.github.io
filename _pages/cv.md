---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 2
description: Curriculum Vitae of Junghyeok Lee.
---

<style>
/* Hide default page title to make a custom CV header */
.post-header {
  display: none;
}

.cv-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 1rem;
}

.cv-header h1 {
  margin: 0;
  font-size: 2rem;
  font-weight: 600;
}

.cv-download-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 2.2rem;
  height: 2.2rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 999px;
  color: var(--global-text-color);
  text-decoration: none;
  transition: all 0.15s ease-in-out;
}

.cv-download-icon:hover {
  color: var(--global-theme-color);
  border-color: var(--global-theme-color);
  text-decoration: none;
}

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
</style>

<div class="cv-header">
  <h1>CV</h1>

  <a
    class="cv-download-icon"
    href="{{ '/assets/pdf/CV_Junghyeok_Lee_2026_07.pdf' | relative_url }}"
    target="_blank"
    aria-label="Download CV PDF"
    title="Download CV PDF"
  >
    <i class="fa-solid fa-file-pdf"></i>
  </a>
</div>

<div class="cv-pdf-container">
  <iframe
    src="https://docs.google.com/gview?embedded=true&url=https://jhy20k.github.io/assets/pdf/CV_Junghyeok_Lee_2026_07.pdf"
    title="Junghyeok Lee CV">
  </iframe>
</div>
