---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Shenzhen, China</p>

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

<div class="agenda-section">
  <p class="agenda-question">How can assessment better inform what support a person needs?</p>

  <div class="agenda-map" aria-label="Research agenda connecting development and assessment to individual needs and support">
    <div class="agenda-sources">
      <div class="agenda-source">
        <span class="agenda-dot" aria-hidden="true"></span>
        <span>Understand development</span>
      </div>
      <div class="agenda-source">
        <span class="agenda-dot" aria-hidden="true"></span>
        <span>Characterize differences through assessment</span>
      </div>
    </div>

    <svg class="agenda-merge" viewBox="0 0 100 180" preserveAspectRatio="none" aria-hidden="true">
      <path d="M0,38 C42,38 46,90 100,90"></path>
      <path d="M0,142 C42,142 46,90 100,90"></path>
    </svg>

    <div class="agenda-focus-column">
      <div class="agenda-focus">Individual<br>needs</div>
      <div class="agenda-downline" aria-hidden="true"></div>
      <div class="agenda-step"><span class="agenda-small-dot" aria-hidden="true"></span>Match support</div>
      <div class="agenda-downline agenda-downline-short" aria-hidden="true"></div>
      <div class="agenda-step"><span class="agenda-small-dot" aria-hidden="true"></span>Monitor &amp; adapt</div>
      <div class="agenda-downline agenda-downline-short" aria-hidden="true"></div>
      <div class="agenda-step agenda-final"><span class="agenda-small-dot" aria-hidden="true"></span>Accessible support</div>
    </div>
  </div>
</div>

<style>
.agenda-section {
  margin: 3.4rem 0 2.6rem;
  padding-top: 2rem;
  border-top: 1px solid var(--global-divider-color);
}

.agenda-question {
  margin: 0 0 2.3rem;
  text-align: center;
  font-size: 1.16rem;
  font-weight: 500;
  color: var(--global-text-color);
}

.agenda-map {
  display: grid;
  grid-template-columns: minmax(250px, 1.15fr) 100px minmax(220px, 0.9fr);
  align-items: start;
  max-width: 820px;
  margin: 0 auto;
}

.agenda-sources {
  min-height: 180px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1.1rem 0;
}

.agenda-source {
  display: flex;
  align-items: center;
  gap: 0.72rem;
  min-height: 48px;
  color: var(--global-text-color);
  font-size: 1rem;
  line-height: 1.35;
}

.agenda-dot,
.agenda-small-dot {
  flex: 0 0 auto;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--global-theme-color);
}

.agenda-merge {
  width: 100%;
  height: 180px;
  overflow: visible;
}

.agenda-merge path {
  fill: none;
  stroke: var(--global-divider-color);
  stroke-width: 1.8;
  vector-effect: non-scaling-stroke;
  stroke-linecap: round;
}

.agenda-focus-column {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.agenda-focus {
  width: 132px;
  height: 132px;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  border: 2px solid var(--global-theme-color);
  border-radius: 50%;
  color: var(--global-text-color);
  font-size: 1.08rem;
  font-weight: 500;
  line-height: 1.25;
  background: var(--global-bg-color);
}

.agenda-downline {
  width: 1px;
  height: 34px;
  background: var(--global-divider-color);
}

.agenda-downline-short {
  height: 24px;
}

.agenda-step {
  display: flex;
  align-items: center;
  gap: 0.55rem;
  min-width: 150px;
  justify-content: center;
  color: var(--global-text-color);
  font-size: 0.98rem;
}

.agenda-small-dot {
  width: 7px;
  height: 7px;
}

.agenda-final {
  color: var(--global-theme-color);
  font-weight: 500;
}

@media (max-width: 760px) {
  .agenda-section {
    margin-top: 2.7rem;
  }

  .agenda-question {
    text-align: left;
    font-size: 1.08rem;
    margin-bottom: 1.8rem;
  }

  .agenda-map {
    grid-template-columns: 1fr;
    gap: 1rem;
  }

  .agenda-sources {
    min-height: 0;
    gap: 1rem;
    padding: 0;
  }

  .agenda-merge {
    display: none;
  }

  .agenda-focus-column::before {
    content: "↓";
    color: var(--global-text-color-light);
    margin-bottom: 0.9rem;
  }

  .agenda-focus {
    width: 118px;
    height: 118px;
    font-size: 1rem;
  }
}
</style>
