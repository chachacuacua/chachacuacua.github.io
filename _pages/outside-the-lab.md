---
layout: page
title: outside the lab
permalink: /outside-the-lab/
description: A small timeline of the places, experiences, and companions that have shaped me outside research.
nav: true
nav_order: 5
---

<div class="life-timeline" id="lifeTimeline">
  <svg class="life-path" id="lifePathSvg" aria-hidden="true">
    <path id="lifePath" fill="none"></path>
  </svg>

  <details class="life-stop life-left">
    <summary>
      <span class="life-node" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">1–7</span>
        <span class="life-place">Xinjiang</span>
        <span class="life-subtitle">Where it started</span>
        <span class="life-hint"></span>
      </span>
    </summary>
    <div class="life-panel">
      <p>I spent my earliest years in Xinjiang with my grandparents, surrounded by wide landscapes, long summers, and some of the food I still miss the most.</p>
      <div class="life-gallery life-gallery-two">
        <img src="{{ '/assets/img/outside/xinjiang-childhood-landscape.jpg' | relative_url }}" alt="A landscape from Xinjiang connected to my childhood" loading="lazy">
        <img src="{{ '/assets/img/outside/xinjiang-childhood-food.jpg' | relative_url }}" alt="Food from Xinjiang that reminds me of childhood" loading="lazy">
      </div>
    </div>
  </details>

  <details class="life-stop life-right">
    <summary>
      <span class="life-node" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">7–15</span>
        <span class="life-place">Beijing</span>
        <span class="life-subtitle">A wider map</span>
        <span class="life-hint"></span>
      </span>
    </summary>
    <div class="life-panel">
      <p>I moved to Beijing when I was seven and spent most of my childhood there. It was a very different rhythm from Xinjiang—busier, denser, and full of new things and places to explore. Living there made me increasingly aware that access to educational and cultural resources could vary greatly across places. It was also where reading became one of my favorite ways of discovering a world beyond my immediate surroundings.</p>
      <div class="life-gallery life-gallery-two">
        <img src="{{ '/assets/img/outside/beijing-childhood-city.jpg' | relative_url }}" alt="A Beijing scene connected to my childhood" loading="lazy">
        <img src="{{ '/assets/img/outside/beijing-childhood-reading.jpg' | relative_url }}" alt="A reading memory from my childhood in Beijing" loading="lazy">
      </div>
    </div>
  </details>

  <details class="life-stop life-left">
    <summary>
      <span class="life-node" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">15–18</span>
        <span class="life-place">Xinjiang</span>
        <span class="life-subtitle">Home, made unfamiliar</span>
        <span class="life-hint"></span>
      </span>
    </summary>
    <div class="life-panel">
      <p>I returned to Xinjiang for high school. Coming back to a familiar place at a very different age made it feel strangely unfamiliar. Around this time, I began thinking more seriously about what I might be able to do for other people—and, at the same time, wanting to see a world much larger and farther away than the one I knew.</p>
      <div class="life-gallery life-gallery-one">
        <img src="{{ '/assets/img/outside/xinjiang-highschool-years.jpg' | relative_url }}" alt="A memory from my high-school years in Xinjiang" loading="lazy">
      </div>
    </div>
  </details>

  <details class="life-stop life-right">
    <summary>
      <span class="life-node" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">19–23</span>
        <span class="life-place">Davis, California</span>
        <span class="life-subtitle">Building a life of my own</span>
        <span class="life-hint"></span>
      </span>
    </summary>
    <div class="life-panel">
      <p>Moving to Davis for college was my first time building a life far from home. Somewhere between classes, friends, work, and my cat, Davis gradually became a place I felt deeply attached to.</p>
      <p>It was also where I first worked directly with adults with intellectual and developmental disabilities. That experience changed how I thought about support, independence, and what “useful” work can actually look like in everyday life.</p>
      <div class="life-gallery life-gallery-three">
        <img src="{{ '/assets/img/outside/davis-life.jpg' | relative_url }}" alt="A memory from life in Davis, California" loading="lazy">
        <img src="{{ '/assets/img/outside/davis-cat.jpg' | relative_url }}" alt="My cat during my years in Davis" loading="lazy">
        <img src="{{ '/assets/img/outside/davis-work.jpg' | relative_url }}" alt="A memory connected to my work in Davis" loading="lazy">
      </div>
    </div>
  </details>

  <details class="life-stop life-left">
    <summary>
      <span class="life-node" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">23–25</span>
        <span class="life-place">Hong Kong &amp; Shenzhen</span>
        <span class="life-subtitle">Between places and possibilities</span>
        <span class="life-hint"></span>
      </span>
    </summary>
    <div class="life-panel">
      <p>After returning to China, I found myself moving between places, projects, and new possibilities. Research gradually became something I wanted to build more of my life around, while I also started learning to make things rather than only study them, traveled whenever I could, and continued to take an unreasonable number of photos of my cat.</p>
      <div class="life-gallery life-gallery-three">
        <img src="{{ '/assets/img/outside/recent-cat.jpg' | relative_url }}" alt="A recent photo of my cat" loading="lazy">
        <img src="{{ '/assets/img/outside/recent-travel-01.jpg' | relative_url }}" alt="A recent travel memory" loading="lazy">
        <img src="{{ '/assets/img/outside/recent-travel-02.jpg' | relative_url }}" alt="Another recent travel memory" loading="lazy">
      </div>
    </div>
  </details>

  <div class="life-stop life-right life-next">
    <div class="life-next-summary">
      <span class="life-node life-node-next" aria-hidden="true"></span>
      <span class="life-label">
        <span class="life-age">?</span>
        <span class="life-place">Next</span>
        <span class="life-subtitle">Still figuring it out</span>
      </span>
    </div>
    <div class="life-panel life-next-panel">
      <p>I am still figuring out where the next stop will be.</p>
    </div>
  </div>
</div>

<style>
.life-intro {
  max-width: 700px;
  margin: 0.4rem 0 2.8rem;
  color: var(--global-text-color-light);
  font-size: 1.05rem;
}

.life-timeline {
  position: relative;
  width: 100%;
  margin: 1rem 0 4rem;
  padding: 0.5rem 0 2rem;
}

.life-path {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  overflow: visible;
  pointer-events: none;
  z-index: 0;
}

.life-path path {
  stroke: var(--global-divider-color);
  stroke-width: 2.2;
  stroke-linecap: round;
  vector-effect: non-scaling-stroke;
}

.life-stop {
  position: relative;
  z-index: 1;
  width: 100%;
  margin: 0 0 2.5rem;
}

.life-stop summary,
.life-next-summary {
  position: relative;
  min-height: 92px;
  display: flex;
  align-items: center;
  cursor: pointer;
  list-style: none;
  transition: transform 180ms ease;
}

.life-stop summary::-webkit-details-marker {
  display: none;
}

.life-left summary,
.life-left .life-next-summary {
  padding-left: 13%;
  padding-right: 43%;
}

.life-right summary,
.life-right .life-next-summary {
  padding-left: 43%;
  padding-right: 13%;
  justify-content: flex-end;
  text-align: right;
}

.life-node {
  position: absolute;
  top: 50%;
  width: 20px;
  height: 20px;
  transform: translateY(-50%);
  border-radius: 50%;
  background: var(--global-theme-color);
  border: 4px solid var(--global-bg-color);
  box-shadow: 0 0 0 2px var(--global-theme-color);
  transition: transform 180ms ease, box-shadow 180ms ease;
}

.life-left .life-node {
  left: 7.5%;
}

.life-right .life-node {
  right: 7.5%;
}

.life-stop summary:hover .life-node {
  transform: translateY(-50%) scale(1.18);
  box-shadow: 0 0 0 3px var(--global-theme-color);
}

.life-stop summary:hover .life-label {
  transform: translateY(-2px);
}

.life-label {
  display: flex;
  flex-direction: column;
  transition: transform 180ms ease;
}

.life-age {
  display: block;
  margin-bottom: 0.08rem;
  color: var(--global-theme-color);
  font-size: 0.86rem;
  font-weight: 600;
  letter-spacing: 0.04em;
}

.life-place {
  display: block;
  color: var(--global-text-color);
  font-size: 1.38rem;
  font-weight: 500;
  line-height: 1.2;
}

.life-subtitle {
  display: block;
  margin-top: 0.25rem;
  color: var(--global-text-color-light);
  font-size: 0.98rem;
  font-style: italic;
}

.life-hint {
  display: block;
  margin-top: 0.38rem;
  color: var(--global-text-color-light);
  font-size: 0.72rem;
  opacity: 0.72;
  font-style: normal;
}

.life-hint::after {
  content: "click to open";
}

details[open] .life-hint::after {
  content: "click to close";
}

.life-panel {
  width: 68%;
  margin-top: 0.2rem;
  padding: 1.25rem 1.35rem 1.35rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 1rem;
  background: var(--global-bg-color);
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.035);
  animation: lifeReveal 220ms ease-out;
}

.life-left .life-panel {
  margin-left: 7.5%;
  margin-right: auto;
}

.life-right .life-panel {
  margin-left: auto;
  margin-right: 7.5%;
}

.life-panel p:last-of-type {
  margin-bottom: 1rem;
}

.life-gallery {
  display: grid;
  gap: 0.7rem;
  margin-top: 1rem;
}

.life-gallery-two {
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.life-gallery-three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.life-gallery-one {
  grid-template-columns: minmax(0, 1fr);
  max-width: 540px;
}

.life-gallery img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 0.72rem;
  transition: transform 220ms ease, box-shadow 220ms ease;
}

.life-gallery img:hover {
  transform: scale(1.025);
  box-shadow: 0 8px 22px rgba(0, 0, 0, 0.11);
}

.life-node-next {
  background: var(--global-bg-color);
  box-shadow: 0 0 0 2px var(--global-theme-color);
}

.life-next-summary {
  cursor: default;
}

.life-next-panel {
  border-style: dashed;
  box-shadow: none;
}

@keyframes lifeReveal {
  from { opacity: 0; transform: translateY(-6px); }
  to { opacity: 1; transform: translateY(0); }
}

@media (max-width: 760px) {
  .life-intro {
    margin-bottom: 2rem;
  }

  .life-stop {
    margin-bottom: 1.8rem;
  }

  .life-left summary,
  .life-right summary,
  .life-left .life-next-summary,
  .life-right .life-next-summary {
    min-height: 82px;
    padding-left: 3.5rem;
    padding-right: 0.25rem;
    justify-content: flex-start;
    text-align: left;
  }

  .life-left .life-node,
  .life-right .life-node {
    left: 1rem;
    right: auto;
  }

  .life-panel,
  .life-left .life-panel,
  .life-right .life-panel {
    width: calc(100% - 2.5rem);
    margin-left: 2.5rem;
    margin-right: 0;
    padding: 1rem;
  }

  .life-gallery-two,
  .life-gallery-three {
    grid-template-columns: 1fr;
  }

  .life-gallery img {
    height: auto;
    max-height: 420px;
  }

  .life-place {
    font-size: 1.22rem;
  }
}
</style>

<script>
(function () {
  function drawLifePath() {
    const timeline = document.getElementById('lifeTimeline');
    const svg = document.getElementById('lifePathSvg');
    const path = document.getElementById('lifePath');
    if (!timeline || !svg || !path) return;

    const timelineRect = timeline.getBoundingClientRect();
    const nodes = Array.from(timeline.querySelectorAll('.life-node'));
    const points = nodes.map(function (node) {
      const rect = node.getBoundingClientRect();
      return {
        x: rect.left + rect.width / 2 - timelineRect.left,
        y: rect.top + rect.height / 2 - timelineRect.top
      };
    });

    const width = Math.max(1, timeline.clientWidth);
    const height = Math.max(1, timeline.scrollHeight);
    svg.setAttribute('viewBox', '0 0 ' + width + ' ' + height);
    svg.setAttribute('preserveAspectRatio', 'none');

    if (points.length < 2) return;

    let d = 'M ' + points[0].x + ' ' + points[0].y;
    for (let i = 1; i < points.length; i++) {
      const prev = points[i - 1];
      const curr = points[i];
      const midY = prev.y + (curr.y - prev.y) / 2;
      d += ' C ' + prev.x + ' ' + midY + ', ' + curr.x + ' ' + midY + ', ' + curr.x + ' ' + curr.y;
    }
    path.setAttribute('d', d);
  }

  const details = Array.from(document.querySelectorAll('#lifeTimeline details.life-stop'));
  details.forEach(function (item) {
    item.addEventListener('toggle', function () {
      if (item.open) {
        details.forEach(function (other) {
          if (other !== item) other.open = false;
        });
      }
      window.setTimeout(drawLifePath, 40);
      window.setTimeout(drawLifePath, 260);
    });
  });

  window.addEventListener('resize', drawLifePath);
  window.addEventListener('load', drawLifePath);
  document.querySelectorAll('#lifeTimeline img').forEach(function (img) {
    img.addEventListener('load', drawLifePath);
  });

  drawLifePath();
})();
</script>