---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 4
description:
---

<div class="cv-download-page">
  <a class="cv-download-button" href="{{ '/assets/pdf/Yihan_Zhao_CV202608.pdf' | relative_url }}" download>
    Download CV (PDF)
  </a>
</div>

<style>
.cv-download-page {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  min-height: 220px;
}

.cv-download-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.8rem 1.25rem;
  border: 1px solid var(--global-theme-color);
  border-radius: 0.6rem;
  color: var(--global-theme-color);
  font-weight: 500;
  text-decoration: none;
  transition: background 0.15s ease, color 0.15s ease;
}

.cv-download-button:hover {
  background: var(--global-theme-color);
  color: var(--global-bg-color);
  text-decoration: none;
}
</style>
