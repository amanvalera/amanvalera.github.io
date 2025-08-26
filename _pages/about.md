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

/* Sidebar base */
.sidebar {
  left: 2em; /* small offset from edge */
}

/* Full-page snap scroll */
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  scroll-snap-type: y mandatory;
  overscroll-behavior-y: contain;
}

/* Container is just a wrapper, not scrollable */
.snap-container {
  height: auto;
  overflow: visible;
  margin: 0;
  padding: 0;
}

/* Snap targets */
.snap-section,
footer.site-footer {
  min-height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  box-sizing: border-box;
  color: #f5f5f5;

  /* snap behavior */
  scroll-snap-align: start;
  scroll-margin-top: var(--masthead-height, 60px); /* prevent hiding under nav */

  /* sidebar awareness on desktop */
  padding-left: calc(var(--sidebar-width, 320px) + var(--gutter, 2rem));
  padding-right: var(--gutter, 2rem);
}

/* Inner content */
.content-wrap {
  max-width: 65ch;
  margin: 0;
  width: 100%;
  box-sizing: border-box;
}

/* Typography */
.content-wrap h1 {
  font-size: clamp(2rem, 4vw, 3rem);
  margin-bottom: 1rem;
  font-weight: 700;
}
.content-wrap h2 {
  font-size: clamp(1.2rem, 2vw, 1.6rem);
  color: #ccc;
  margin-bottom: 2rem;
  font-weight: 400;
}
.content-wrap p, .content-wrap ul {
  font-size: 1rem;
  line-height: 1.6;
  color: #ddd;
}
.content-wrap ul { list-style: none; padding-left: 0; }
.content-wrap li { margin: .75rem 0; }

/* Section gradients */
.hero     { background: radial-gradient(circle at 75% 20%, #2c2655 0%, transparent 70%) #111; }
.services { background: radial-gradient(circle at 20% 10%, #253b59 0%, transparent 70%) #111; }
.about    { background: radial-gradient(circle at 80% 80%, #2c4c3b 0%, transparent 70%) #111; }
.impact   { background: radial-gradient(circle at 20% 80%, #5a2f3b 0%, transparent 70%) #111; }
.focus    { background: #111; }

/* Desktop sidebar sticky beside content */
@media (min-width: 57.8125em) {
  #main {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
  }

  .sidebar.sticky {
    position: sticky;
    top: var(--masthead-height, 60px);
    margin-left: 2em;
    flex: 0 0 var(--sidebar-width, 320px);
    height: calc(100vh - var(--masthead-height, 60px));
    overflow-y: auto;
  }

  .snap-container {
    flex: 1;
  }
}

/* Mobile-friendly layout */
@media (max-width: 768px) {
  .sidebar.sticky {
    position: relative;   /* no sticky on mobile */
    top: auto;
    margin: 0;
    width: 100%;
    background: #111; /* optional */
    z-index: 1000;
  }

  .snap-section {
    padding-top: 1rem;
    padding-left: var(--gutter, 1rem);
    padding-right: var(--gutter, 1rem);
  }

  .content-wrap {
    max-width: 100%;
    padding-left: var(--gutter, 1rem);
    padding-right: var(--gutter, 1rem);
  }
}

/* Footer styling */
footer.site-footer {
  display: flex;
  align-items: center;
  justify-content: center;
  color: #f5f5f5;
  background: #111;
  margin: 0 !important;
  padding: 0 !important;
}
</style>

<div class="snap-container">

<section class="snap-section hero">
  <div class="content-wrap">
    <h1>Reimagining the future through the language of data.</h1>
    <h2>I don’t just analyze it — I transform it into insight.</h2>
  </div>
</section>

<section class="snap-section services">
  <div class="content-wrap">
    <h1>What I deliver</h1>
    <ul>
      <li><strong>Business Intelligence</strong> — Dashboards, SQL data models, Power BI, Looker Studio</li>
      <li><strong>Predictive Analytics</strong> — End-to-end ML systems, sports forecasting (e.g. IPL win predictions)</li>
      <li><strong>Frontier AI Research</strong> — Deep Learning, Agentic AI, Biologically Inspired Computation</li>
    </ul>
  </div>
</section>

<section class="snap-section about">
  <div class="content-wrap">
    <h1>I’m a Data Scientist & Machine Learning Engineer</h1>
    <p>Expertise in <strong>sports analytics</strong> and <strong>business intelligence</strong> — bridging pipelines, models, and product to deliver clarity.</p>
  </div>
</section>

<section class="snap-section impact">
  <div class="content-wrap">
    <h1>End-to-end systems that ship</h1>
    <p>From SQL pipelines and dashboards to predictive ML models — including an <strong>84% F1</strong> in live IPL match predictions.</p>
  </div>
</section>

<section class="snap-section focus">
  <div class="content-wrap">
    <h1>Practical impact today. Exploring tomorrow.</h1>
    <p><strong>Practical today</strong> — analytics pipelines, dashboards, and models that drive decisions.<br>
       <strong>Exploring tomorrow</strong> — agentic approaches, biologically inspired computation, and statistical modeling.</p>
  </div>
</section>

</div>
