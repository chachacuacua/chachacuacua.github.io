---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

I am a Lab Manager and Research Assistant at the SEED Lab, The Chinese University of Hong Kong, Shenzhen. My work focuses on early social development and developmental assessment, with particular interests in autism, family processes, and family-centered support.

Across my projects, I am interested in how we can move from observing developmental differences to understanding what those differences mean for an individual's needs. I study social attention, social communication, and parent–child interaction across children and contexts, using behavioral and physiological measures to characterize variation in development.

I am also interested in how assessment can connect more directly to intervention. In particular, I want to explore how interactive technologies—including serious games, child–AI interaction, child–robot interaction, and telehealth—can help translate developmental evidence into support that is more individualized, engaging, and accessible.

<h2 style="margin-top: 3.2rem;">Research interests</h2>

- **Early social development:** parent–child interaction · social motivation
- **Autism research:** early identification and intervention · individualized and family-centered support
- **Family processes:** coparenting · parent–child relationships · transition to parenthood · family systems
- **Technology-mediated assessment:** child–AI/robot interaction · serious games · telehealth

<section class="rq-section" aria-labelledby="rq-title">
  <h2 id="rq-title">My broader research questions</h2>
  <p class="rq-overview">How can assessment better inform what support a person needs—and how can that support be delivered in practice?</p>

  <div class="rq-grid">
    <article class="rq-card">
      <div class="rq-number">01</div>
      <h3>Personalization</h3>
      <p class="rq-question">Who needs what?</p>
      <p class="rq-description">Moving beyond broad diagnostic or developmental labels toward a more precise understanding of individual differences and needs.</p>
    </article>

    <div class="rq-connector" aria-hidden="true">
      <span class="rq-line"></span>
      <span class="rq-arrow">→</span>
    </div>

    <article class="rq-card">
      <div class="rq-number">02</div>
      <h3>Accessibility &amp; implementation</h3>
      <p class="rq-question">How can we actually deliver it?</p>
      <p class="rq-description">Moving from identifying what support may fit a person to making that support feasible, usable, and accessible in real-world settings.</p>
    </article>
  </div>
</section>

<style>
.rq-section {
  margin: 3.5rem 0 2.8rem;
  padding-top: 2.2rem;
  border-top: 1px solid var(--global-divider-color);
}

.rq-section h2 {
  margin-bottom: 0.6rem;
}

.rq-overview {
  max-width: 760px;
  margin: 0 0 2.2rem;
  color: var(--global-text-color-light);
  font-size: 1.04rem;
  line-height: 1.55;
}

.rq-grid {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 72px minmax(0, 1fr);
  align-items: stretch;
  gap: 0;
}

.rq-card {
  min-height: 230px;
  padding: 1.45rem 1.5rem 1.4rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 1rem;
  background: var(--global-bg-color);
}

.rq-number {
  margin-bottom: 1.05rem;
  color: var(--global-theme-color);
  font-size: 0.78rem;
  font-weight: 600;
  letter-spacing: 0.08em;
}

.rq-card h3 {
  margin: 0 0 0.55rem;
  color: var(--global-text-color);
  font-size: 1.28rem;
  font-weight: 600;
}

.rq-question {
  margin: 0 0 1rem;
  color: var(--global-theme-color);
  font-size: 1.03rem;
  font-weight: 500;
}

.rq-description {
  margin: 0;
  color: var(--global-text-color);
  font-size: 0.98rem;
  line-height: 1.55;
}

.rq-connector {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.rq-line {
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  height: 1px;
  background: var(--global-divider-color);
}

.rq-arrow {
  position: relative;
  z-index: 1;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: var(--global-bg-color);
  color: var(--global-theme-color);
  font-size: 1.15rem;
}

@media (max-width: 760px) {
  .rq-section {
    margin-top: 2.8rem;
  }

  .rq-grid {
    grid-template-columns: 1fr;
  }

  .rq-card {
    min-height: 0;
  }

  .rq-connector {
    min-height: 58px;
  }

  .rq-line {
    left: 50%;
    right: auto;
    top: 0;
    bottom: 0;
    width: 1px;
    height: auto;
  }

  .rq-arrow {
    transform: rotate(90deg);
  }
}
</style>
