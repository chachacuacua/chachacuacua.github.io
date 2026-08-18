---
layout: page
title: Projects
permalink: /projects/
description: Selected research and design projects.
nav: true
nav_order: 1
---

<p class="projects-intro">Selected projects spanning early social development, family-centered research, and technology-mediated support.</p>

<section class="project-block">
  <div class="project-heading">
    <div class="project-index">01</div>
    <div>
      <h2>Parent–Child Interaction and Development</h2>
      <p class="project-subtitle"><em>Family Time / 亲子时光</em> · Infants and toddlers · Multimodal developmental research</p>
    </div>
  </div>

  <div class="project-text-grid">
    <div>
      <h3>About the project</h3>
      <p>This longitudinal research program examines early social development across attention, physiology, behavior, and parent-reported characteristics. The broader project combines eye-tracking, EEG and fNIRS, parent–child interaction, and questionnaires to characterize social-developmental trajectories and explore early markers relevant to autism and social communication.</p>
    </div>

    <div>
      <h3>My role</h3>
      <p>I manage day-to-day research operations with approximately 100 families of infants and toddlers aged 5–24 months, including family follow-up, scheduling and coordination of ~230 experimental visits, parent–child interaction sessions, Tobii Pro eye-tracking data collection and analysis, and RA scheduling.</p>
      <p>I completed SCS training and qualified as a reliable coder for recorded parent–child interactions.</p>
    </div>
  </div>

  <p class="project-methods"><strong>Methods:</strong> eye-tracking · parent–child interaction · longitudinal follow-up · observational coding · R / RStudio</p>
</section>

<section class="project-block">
  <div class="project-heading">
    <div class="project-index">02</div>
    <div>
      <h2>Growing with Nature</h2>
      <p class="project-subtitle"><em>Growing with Nature / 自然童行</em> · Children aged 2–5 · Nature exposure &amp; development</p>
    </div>
  </div>

  <div class="project-text-grid">
    <div>
      <h3>About the project</h3>
      <p>The Growing with Nature Project examines how nature exposure and nature relatedness relate to wellbeing, emotion and behavior regulation, attention, and broader developmental functioning in children aged 2–5 years, including autistic children. The study combines 12-week longitudinal tracking of nature exposure with pre/post questionnaires, in-lab research visits, eye-tracking, parent–child interaction, and parent report.</p>
    </div>

    <div>
      <h3>My role</h3>
      <p>I design and lead nature-based outdoor activities for approximately 50 participating families and coordinate team assignments and fieldwork procedures.</p>
    </div>
  </div>

  <p class="project-methods"><strong>Methods:</strong> field research · longitudinal tracking · eye-tracking · parent–child interaction · parent report</p>
</section>

<section class="project-block">
  <div class="project-heading">
    <div class="project-index">03</div>
    <div>
      <h2>The Gift of the Tenth Month</h2>
      <p class="project-subtitle"><em>十月之礼</em> · Partner-inclusive prenatal education · Serious game · Godot Engine 4</p>
    </div>
  </div>

  <div class="project-text-grid">
    <div>
      <h3>About the project</h3>
      <p><em>The Gift of the Tenth Month</em> is a partner-inclusive prenatal education serious game designed to move prenatal learning beyond information delivery toward situated practice, emotional readiness, and concrete partner participation. Players move through home, town, and hospital settings, collect knowledge fragments, complete clinical questlines, and receive low-pressure feedback from both expectant-mother and partner perspectives.</p>
      <p>The current playable slice centers on a Week-16 Down syndrome screening scenario that combines daily preparation, hospital navigation, risk language, and professional interpretation.</p>
    </div>

    <div>
      <h3>My role</h3>
      <p>I lead the design and development of the prototype in Godot Engine 4, translating prenatal health and family-support content into role-based gameplay, NPC dialogue, home–town–hospital scenarios, clinical questlines, and interactive learning tasks.</p>
      <p>I also conducted formative evaluation with 22 participants and use the feedback to guide iterative refinement, including stronger and more playable partner-route interactions. The project has been accepted as a Work-in-Progress paper at CHI PLAY 2026; the proceedings link will be posted when available.</p>
    </div>
  </div>

  <p class="project-methods"><strong>Tools:</strong> Godot Engine 4 · serious games · interaction design · formative evaluation · family-centered design</p>
</section>

<style>
.projects-intro {
  max-width: 760px;
  margin: 0.35rem 0 2.2rem;
  color: var(--global-text-color-light);
  font-size: 1.04rem;
  line-height: 1.6;
}

.project-block {
  margin: 0 0 3.4rem;
  padding-top: 1.8rem;
  border-top: 1px solid var(--global-divider-color);
}

.project-heading {
  display: grid;
  grid-template-columns: 52px minmax(0, 1fr);
  gap: 0.8rem;
  align-items: start;
  margin-bottom: 1.45rem;
}

.project-index {
  padding-top: 0.35rem;
  color: var(--global-theme-color);
  font-size: 0.82rem;
  font-weight: 600;
  letter-spacing: 0.08em;
}

.project-heading h2 {
  margin: 0 0 0.4rem;
  color: var(--global-text-color);
  font-size: 1.55rem;
  font-weight: 600;
  line-height: 1.3;
}

.project-subtitle {
  margin: 0;
  color: var(--global-text-color-light);
  font-size: 0.98rem;
  line-height: 1.5;
}

.project-text-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 2.2rem;
}

.project-text-grid h3 {
  margin: 0 0 0.65rem;
  color: var(--global-text-color);
  font-size: 1rem;
  font-weight: 600;
}

.project-text-grid p {
  margin-bottom: 0.72rem;
  line-height: 1.63;
}

.project-methods {
  margin: 1.05rem 0 0;
  padding-top: 0.85rem;
  border-top: 1px solid color-mix(in srgb, var(--global-divider-color) 65%, transparent);
  color: var(--global-text-color-light);
  font-size: 0.93rem;
  line-height: 1.55;
}

.project-methods strong {
  color: var(--global-text-color);
}

@media (max-width: 760px) {
  .project-block {
    margin-bottom: 3rem;
  }

  .project-heading {
    grid-template-columns: 38px minmax(0, 1fr);
  }

  .project-heading h2 {
    font-size: 1.35rem;
  }

  .project-text-grid {
    grid-template-columns: 1fr;
    gap: 1.15rem;
  }
}
</style>
