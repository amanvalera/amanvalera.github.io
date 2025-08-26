---
permalink: /
title: "Aman Valera – Data Scientist & AI Innovator"
layout: single
classes: wide
author_profile: true
---

<style>
/* Hide page title (kept for SEO) */
.page-title,
h1.page__title,
header.page__header { display: none !important; }

/* Remove container restrictions */
.page__inner-wrap,
.page__content {
  width: 100% !important;
  max-width: 100% !important;
  margin: 0 !important;
  padding: 0 !important;
  box-sizing: border-box;
}

#main {
  margin: 0 !important;
  padding: 0 !important;
  width: 100% !important;
  max-width: 100% !important;
  box-sizing: border-box;
}

/* Sidebar default (desktop = fixed) */
.sidebar {
  position: fixed !important;
  top: var(--masthead-height, 3.5rem);
  padding-left: var(--masthead-height, 3.5rem);
  width: var(--sidebar-width, 300px);
  height: calc(100vh - var(--masthead-height, 3.5rem));
  overflow-y: auto;
  z-index: 100;
}

/* Desktop page layout */
@media (min-width: 57.8125em) {
  .page {
    width: 100% !important;
    float: none !important;
    margin: 0 !important;
    padding: 0 !important;
  }
}

/* Snap scroll only on container */
.snap-container {
  height: 100vh;
  overflow-y: scroll;
  scroll-snap-type: y mandatory;
  overscroll-behavior-y: contain;
  margin: 0;
  padding: 0;
}

/* Each section */
.snap-section {
  min-height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  scroll-snap-align: start;
  box-sizing: border-box;
  padding-left: calc(var(--sidebar-width, 320px) + var(--gutter, 2rem));
  padding-right: var(--gutter, 2rem);
  color: #f5f5f5;
}

/* Inner content */
.content-wrap {
  max-width: 100% !important;  /* let it stretch full width */
  width: 100% !important;
  margin: 0;
  box-sizing: border-box;
}

/* Typography */
.kicker {
  text-transform: uppercase;
  letter-spacing: .15em;
  font-size: .85rem;
  font-weight: 600;
  color: #aaa;
  margin-bottom: .5rem;
}
.content-wrap h1 {
  font-size: clamp(2.5rem, 5vw, 4rem);
  margin-bottom: 1rem;
  font-weight: 700;
}
.content-wrap h2 {
  font-size: clamp(1.2rem, 2vw, 1.6rem);
  color: #ccc;
  margin-bottom: 1rem;
  font-weight: 600;
}
.content-wrap p {
  font-size: 1rem;
  line-height: 1.6;
  color: #ddd;
}
.content-wrap ul {
  list-style: disc;
  padding-left: 1.5rem;
  margin: 1rem 0;
}
.content-wrap li {
  margin: 0.5rem 0;
  color: #ddd;
}

/* Pills + buttons */
.pill {
  display: inline-block;
  background: #363636;
  color: #eaeaea;
  border-radius: 999px;
  padding: .45rem .9rem;
  margin: .25rem .35rem .35rem 0;
  font-size: .95rem;
}
.cta {
  display: inline-block;
  padding: .9rem 1.15rem;
  border-radius: 12px;
  font-weight: 700;
  text-decoration: none;
}
.cta-primary { background: #9b87f5; color: #0e0a21; }
.cta-ghost { border: 1px solid #444; color: #f5f5f5; margin-left: .5rem; }

/* Section gradients */
.hero     { background: radial-gradient(circle at 75% 20%, #2c2655 0%, transparent 70%) #111; }
.services { background: radial-gradient(circle at 20% 10%, #253b59 0%, transparent 70%) #111; }
.about    { background: radial-gradient(circle at 80% 80%, #2c4c3b 0%, transparent 70%) #111; }
.impact   { background: radial-gradient(circle at 20% 80%, #5a2f3b 0%, transparent 70%) #111; }
.focus    { background: #111; }

/* Mobile adjustments */
@media (max-width: 768px) {
  .sidebar {
    position: sticky !important;
    top: var(--masthead-height, 3.5rem);
    left: 0 !important;
    width: 100% !important;
    height: auto !important;
    margin: 0;
    padding: 1rem;
    background: #111;
    border-radius: 0;
  }

  .snap-section {
    padding-left: var(--gutter, 1rem) !important;
    padding-right: var(--gutter, 1rem) !important;
    padding-top: calc(var(--masthead-height, 3.5rem) + 1rem);
  }

  .content-wrap {
    max-width: 100%;
    padding: 0 var(--gutter, 1rem);
  }
}

/* Kill empty meta block that creates extra gap */
.page__meta {
  display: none !important;
  margin: 0 !important;
  padding: 0 !important;
}

/* Footer reset (NOT snapping) */
.page__footer {
  margin: 0 !important;
  padding: 0 !important;
}
footer.site-footer {
  min-height: auto;
  scroll-snap-align: none !important;
  background: #111;
  color: #f5f5f5;
  margin: 0 !important;
  padding: 2rem;
}

/* Override body padding-bottom (remove 9em gap) */
body {
  padding-bottom: 0 !important;
}
  
/* Grid for services */
.grid {
  display: grid;
  gap: 1.5rem;
}
.grid-3 {
  grid-template-columns: repeat(3, 1fr);
}
@media (max-width: 900px) {
  .grid-3 {
    grid-template-columns: 1fr; /* stack on mobile */
  }
}

/* Card styling */
.card {
  background: #1a1a1a;
  border-radius: 16px;
  padding: 1.5rem;
  box-shadow: 0 6px 20px rgba(0,0,0,0.25);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.35);
}
.card h2 {
  margin-top: 0;
  margin-bottom: 0.75rem;
  font-size: 1.4rem;
  color: #fff;
}
.card p {
  margin: 0;
  color: #ccc;
}
</style>

<div class="snap-container">

<!-- HERO -->
<section class="snap-section hero" id="hero">
  <div class="content-wrap">
    <div class="kicker">AMAN VALERA</div>
    <h1>I don’t just analyze data. I turn it into decisions.</h1>
    <h2>From sports to business, I build systems that explain the present and predict what’s ahead.</h2>
    <div style="margin-top:1.6rem;">
      <a class="cta cta-primary" href="#services">See Services</a>
      <a class="cta cta-ghost" href="#impact">See Results</a>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section class="snap-section services" id="services">
  <div class="content-wrap">
    <div class="kicker">Services</div>
    <h1>What I deliver</h1>

    <div class="grid grid-3" style="margin-top:1.5rem;">
      <div class="card">
        <h2>Business Intelligence</h2>
        <p>Dashboards and SQL pipelines that give leaders a clear view of performance. Power BI and Looker Studio included.</p>
      </div>
      <div class="card">
        <h2>Predictive Analytics</h2>
        <p>Machine learning that drives strategy — including <strong>84% F1 accuracy</strong> on IPL predictions.</p>
      </div>
      <div class="card">
        <h2>AI Research</h2>
        <p>Exploring agentic systems, deep learning, and biologically inspired methods for the next generation of analytics.</p>
      </div>
    </div>

    <div style="margin-top:1rem;">
      <span class="pill">Power BI</span><span class="pill">Looker Studio</span><span class="pill">SQL</span>
      <span class="pill">Python</span><span class="pill">scikit-learn</span><span class="pill">AWS</span>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="snap-section about" id="about">
  <div class="content-wrap">
    <div class="kicker">Identity</div>
    <h1>Clarity from data</h1>
    <p>I work across <strong>sports analytics</strong> and <strong>business intelligence</strong>. From pipelines to models to dashboards, I connect every layer into systems that support real decisions.</p>
    <div style="margin-top:1.6rem;">
      <a class="cta cta-primary" href="/projects/">View Projects</a>
      <a class="cta cta-ghost" href="mailto:youremail@example.com">Contact</a>
    </div>
  </div>
</section>

<!-- IMPACT -->
<section class="snap-section impact" id="impact">
  <div class="content-wrap">
    <div class="kicker">Impact</div>
    <h1>Results</h1>
    <ul>
      <li>SQL pipelines and dashboards in production.</li>
      <li>Live predictive models delivering <strong>84% F1</strong> during IPL matches.</li>
      <li>Research applied in working systems, not just theory.</li>
    </ul>
    <div style="margin-top:1.6rem;">
      <a class="cta cta-primary" href="/projects/">Explore the work</a>
      <a class="cta cta-ghost" href="#hero">Back to top</a>
    </div>
  </div>
</section>

<!-- FOCUS -->
<section class="snap-section focus" id="focus">
  <div class="content-wrap">
    <div class="kicker">Focus</div>
    <h1>Now and next</h1>
    <p><strong>Now:</strong> dashboards, pipelines, and predictive models used every day.<br>
       <strong>Next:</strong> adaptive intelligence and agentic AI expanding how decisions are made.</p>
  </div>
</section>

</div>
