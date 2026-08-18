---
layout: page
permalink: /publications/
title: Publications
description: Publications and conference presentations.
nav: true
nav_order: 2
---

<div class="pub-page">
  <section class="pub-section">
    <div class="pub-section-label">Publication</div>

    <article class="pub-item">
      <div class="pub-year">2026</div>
      <div class="pub-content">
        <h2>The Gift of the Tenth Month: Early Design of a Partner-Inclusive Prenatal Education Serious Game</h2>
        <p class="pub-authors"><strong>Yihan Zhao</strong>, Liying Zhang, Ke Li, Sitong Ke, Songqi Lu, and Guangyu Zeng</p>
        <p class="pub-venue"><em>CHI PLAY 2026 Companion</em></p>
        <p class="pub-status">Accepted. Proceedings link will be posted when available.</p>
      </div>
    </article>
  </section>

  <section class="pub-section">
    <div class="pub-section-label">Conference presentation</div>

    <article class="pub-item">
      <div class="pub-year">2026</div>
      <div class="pub-content">
        <h2>Computational Modeling of Facial Trustworthiness Perception on Action Units Using Machine Learning</h2>
        <p class="pub-authors">Ke Li, Y. Chen, <strong>Yihan Zhao</strong>, and Guangyu Zeng</p>
        <p class="pub-venue"><em>14th Conference for Chinese Psychologists</em></p>
        <p class="pub-status">Oral presentation.</p>
      </div>
    </article>
  </section>
</div>

<style>
.pub-page {
  margin-top: 2.2rem;
}

.pub-section {
  margin-bottom: 3.2rem;
}

.pub-section-label {
  margin-bottom: 1.25rem;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid var(--global-divider-color);
  color: var(--global-theme-color);
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.pub-item {
  display: grid;
  grid-template-columns: 72px minmax(0, 1fr);
  gap: 1.35rem;
  align-items: start;
}

.pub-year {
  padding-top: 0.12rem;
  color: var(--global-text-color-light);
  font-size: 1rem;
  font-weight: 500;
}

.pub-content h2 {
  margin: 0 0 0.55rem;
  color: var(--global-text-color);
  font-size: 1.15rem;
  font-weight: 600;
  line-height: 1.4;
}

.pub-authors,
.pub-venue,
.pub-status {
  margin: 0 0 0.28rem;
  line-height: 1.5;
}

.pub-authors {
  color: var(--global-text-color);
}

.pub-venue,
.pub-status {
  color: var(--global-text-color-light);
}

.pub-status {
  margin-top: 0.45rem;
  font-size: 0.94rem;
}

@media (max-width: 620px) {
  .pub-item {
    grid-template-columns: 1fr;
    gap: 0.35rem;
  }

  .pub-year {
    font-size: 0.9rem;
  }
}
</style>
