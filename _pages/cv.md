---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 3
description:
---

<div class="cv-landing">
  <div class="cv-icon" aria-hidden="true">
    <svg viewBox="0 0 48 48" role="img">
      <path d="M14 6h14l8 8v28H14z"></path>
      <path d="M28 6v9h8"></path>
      <path d="M19 24h12M19 30h12M19 36h8"></path>
    </svg>
  </div>

  <div class="cv-kicker">Curriculum Vitae</div>
  <div class="cv-updated">Updated August 2026</div>

  <a class="cv-download-button" href="{{ '/assets/pdf/Yihan_Zhao_CV202608.pdf' | relative_url }}" download>
    <span>Download CV</span>
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path d="M12 3v11m0 0 4-4m-4 4-4-4M5 19h14"></path>
    </svg>
  </a>
</div>

<style>
.cv-landing {
  max-width: 520px;
  margin: 2.4rem auto 4.5rem;
  padding: 3rem 2.4rem 3.1rem;
  text-align: center;
  border: 1px solid var(--global-divider-color);
  border-radius: 1.2rem;
  background: var(--global-bg-color);
}

.cv-icon {
  width: 64px;
  height: 64px;
  margin: 0 auto 1.35rem;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: color-mix(in srgb, var(--global-theme-color) 9%, var(--global-bg-color));
  color: var(--global-theme-color);
}

.cv-icon svg {
  width: 34px;
  height: 34px;
  fill: none;
  stroke: currentColor;
  stroke-width: 1.8;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cv-kicker {
  margin-bottom: 0.35rem;
  font-size: 1.35rem;
  font-weight: 600;
  color: var(--global-text-color);
}

.cv-updated {
  margin-bottom: 1.8rem;
  font-size: 0.94rem;
  color: var(--global-text-color-light);
}

.cv-download-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 0.55rem;
  padding: 0.78rem 1.2rem;
  border: 1px solid var(--global-theme-color);
  border-radius: 0.65rem;
  background: var(--global-theme-color);
  color: var(--global-bg-color);
  font-weight: 600;
  text-decoration: none;
  transition: transform 0.15s ease, opacity 0.15s ease;
}

.cv-download-button svg {
  width: 18px;
  height: 18px;
  fill: none;
  stroke: currentColor;
  stroke-width: 1.8;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cv-download-button:hover {
  color: var(--global-bg-color);
  text-decoration: none;
  opacity: 0.9;
  transform: translateY(-1px);
}

@media (max-width: 600px) {
  .cv-landing {
    margin-top: 1.6rem;
    padding: 2.4rem 1.5rem 2.5rem;
  }
}
</style>
