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
      <p>I also develop and refine study protocols and IRB materials, contribute to research outputs, and train and coordinate 15+ research assistants. I completed SCS training and qualified as a reliable coder for recorded parent–child interactions.</p>
    </div>
  </div>

  <p class="project-methods"><strong>Methods:</strong> eye-tracking · parent–child interaction · longitudinal follow-up · observational coding · R / RStudio</p>

  <div class="project-visuals project-visuals-three" aria-label="Image placeholders for the Parent–Child Interaction and Development project">
    <div class="project-visual-placeholder"><span>Eye-tracking paradigm</span></div>
    <div class="project-visual-placeholder"><span>Interaction observation lab</span></div>
    <div class="project-visual-placeholder"><span>Parent-facing result report</span></div>
  </div>
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
      <p>I design and lead nature-based outdoor activities for approximately 50 participating families and coordinate team assignments and fieldwork procedures. I also support participant coordination and child-facing research procedures across the project’s field and laboratory components.</p>
    </div>
  </div>

  <p class="project-methods"><strong>Methods:</strong> field research · longitudinal tracking · eye-tracking · parent–child interaction · parent report</p>

  <div class="project-visuals project-visuals-two" aria-label="Image placeholders for the Growing with Nature project">
    <div class="project-visual-placeholder project-visual-wide"><span>Experimental procedure &amp; study conditions</span></div>
    <div class="project-visual-placeholder"><span>Nature-based activity</span></div>
  </div>
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

  <div class="project-visuals project-visuals-three" aria-label="Image placeholders for The Gift of the Tenth Month">
    <div class="project-visual-placeholder"><span>Game world / dual routes</span></div>
    <div class="project-visual-placeholder"><span>Hospital questline</span></div>
    <div class="project-visual-placeholder"><span>Boss challenge</span></div>
  </div>
</section>

<style>
.projects-intro {
  max-width: 760px;
  margin: 0.35rem 0 2.6rem;
  color: var(--global-text-color-light);
  font-size: 1.04rem;
  line-height: 1.6;
}

.project-block {
  margin: 0 0 4.4rem;
  padding-top: 2rem;
  border-top: 1px solid var(--global-divider-color);
}

.project-heading {
  display: grid;
  grid-template-columns: 52px minmax(0, 1fr);
  gap: 0.8rem;
  align-items: start;
  margin-bottom: 1.8rem;
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
  gap: 2.4rem;
}

.project-text-grid h3 {
  margin: 0 0 0.75rem;
  color: var(--global-text-color);
  font-size: 1rem;
  font-weight: 600;
}

.project-text-grid p {
  margin-bottom: 0.8rem;
  line-height: 1.65;
}

.project-methods {
  margin: 1.25rem 0 1.5rem;
  color: var(--global-text-color-light);
  font-size: 0.93rem;
  line-height: 1.55;
}

.project-methods strong {
  color: var(--global-text-color);
}

.project-visuals {
  display: grid;
  gap: 0.85rem;
}

.project-visuals-three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.project-visuals-two {
  grid-template-columns: 1.65fr 1fr;
}

.project-visual-placeholder {
  min-height: 180px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 1rem;
  border: 1px dashed var(--global-divider-color);
  border-radius: 0.9rem;
  background: color-mix(in srgb, var(--global-text-color) 2.5%, var(--global-bg-color));
  color: var(--global-text-color-light);
  text-align: center;
  font-size: 0.86rem;
  letter-spacing: 0.02em;
}

.project-visual-wide {
  min-height: 210px;
}

@media (max-width: 760px) {
  .project-block {
    margin-bottom: 3.5rem;
  }

  .project-heading {
    grid-template-columns: 38px minmax(0, 1fr);
  }

  .project-heading h2 {
    font-size: 1.35rem;
  }

  .project-text-grid,
  .project-visuals-three,
  .project-visuals-two {
    grid-template-columns: 1fr;
    gap: 1.2rem;
  }

  .project-visual-placeholder,
  .project-visual-wide {
    min-height: 150px;
  }
}
</style>
