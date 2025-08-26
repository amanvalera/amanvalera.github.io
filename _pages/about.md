---
permalink: /
title: "Aman Valera – Data Scientist & AI Innovator"
layout: single
classes: wide
author_profile: true
---

<style>
:root {
  --masthead-height: 3.5rem;
  --sidebar-width: 300px;
  --gutter: 2rem;
}

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

/* Sidebar */
.sidebar {
  position: fixed !important;
  top: var(--masthead-height);
  left: 2em;
  width: var(--sidebar-width);
  height: calc(100vh - var(--masthead-height));
  overflow-y: auto;
  z-index: 100;
  padding-top: var(--masthead-height);
}

/* Snap container */
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

  /* ✅ uniform padding now, no sidebar offset */
  padding: var(--masthead-height) var(--gutter);
  color: #f5f5f5;
}

/* Inner content fills right side */
.content-wrap {
  max-width: 100% !important;
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
    top: var(--masthead-height);
    left: 0 !important;
    width: 100% !important;
    height: auto !important;
    margin: 0;
    padding: 1rem;
    background: #111;
    border-radius: 0;
  }

  .snap-section {
    padding: calc(var(--masthead-height) + 1rem) var(--gutter) !important;
  }

  .content-wrap {
    max-width: 100%;
    padding: 0 var(--gutter);
  }
}

/* Kill empty meta block */
.page__meta {
  display: none !important;
}

/* Footer */
footer.site-footer {
  background: #111;
  color: #f5f5f5;
  padding: 2rem;
}
</style>

<div class="snap-container">

<!-- HERO -->
<section class="snap-section hero" id="hero">
  <div class="content-wrap">
    <div class="kicker">AMAN VALERA</div>
    <h1>Reimagining the future through the language of data.</h1>
    <h2>I don’t just analyze it — I transform it into insight.</h2>
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
    <div class="grid grid-3" style="margin-top:1.1rem;">
      <div>
        <h2>Business Intelligence</h2>
        <p>Dashboards, SQL data models, Power BI, Looker Studio</p>
      </div>
      <div>
        <h2>Predictive Analytics</h2>
        <p>End-to-end ML systems, sports forecasting (e.g. IPL win predictions)</p>
      </div>
      <div>
        <h2>Frontier AI Research</h2>
        <p>Deep Learning, Agentic AI, Biologically Inspired Computation</p>
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
    <h1>I’m a Data Scientist &amp; Machine Learning Engineer</h1>
    <p>Expertise in <strong>sports analytics</strong> and <strong>business intelligence</strong> — bridging pipelines, models, and product to deliver clarity.</p>
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
    <h1>End-to-end systems that ship</h1>
    <p>From SQL pipelines and dashboards to predictive ML models — including an <strong>84% F1</strong> in live IPL match predictions.</p>
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
    <h1>Practical impact today. Exploring tomorrow.</h1>
    <p><strong>Practical today</strong> — analytics pipelines, dashboards, and models that drive decisions.<br>
       <strong>Exploring tomorrow</strong> — agentic approaches, biologically inspired computation, and statistical modeling.</p>
  </div>
</section>

</div>
