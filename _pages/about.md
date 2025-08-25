---
permalink: /
title: "Aman Valera – Data Scientist & AI Innovator"
layout: single
classes: wide
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
:root{
  --bg:#222; --fg:#f5f5f5; --muted:#bdbdbd; --accent:#9b87f5; --card:#2b2b2b;
  --maxw:1100px;
}
.page, .page__inner-wrap{ background:var(--bg); color:var(--fg); }
.page__content{ padding:0; }
.page-title, 
h1.page__title, 
header.page__header {
  display: none !important;
}

.snap{ height:100vh; overflow-y:auto; scroll-snap-type:y mandatory; overscroll-behavior-y:contain; }
.section{ min-height:100vh; scroll-snap-align:start; display:flex; align-items:center; }
.wrap{ width:100%; max-width:var(--maxw); margin:0 auto; padding:6rem 2rem; }

h1{ font-size: clamp(2.6rem, 6vw, 5rem); line-height:1.05; margin:0 0 1rem 0; }
h2{ font-size: clamp(1.4rem, 3vw, 2rem); color:var(--muted); font-weight:600; margin:0 0 .25rem 0;}
.lead{ font-size: clamp(1.1rem, 2vw, 1.35rem); color:var(--muted); max-width: 60ch; }
.kicker{ letter-spacing:.18em; text-transform:uppercase; font-size:.82rem; color:var(--muted); margin-bottom:.5rem; }

.card{ background:var(--card); border-radius:20px; padding:1.25rem 1.4rem; box-shadow:0 10px 30px rgba(0,0,0,.25); }
.grid{ display:grid; gap:1.1rem; }
.grid-3{ grid-template-columns:repeat(3,minmax(0,1fr)); }
@media (max-width: 900px){ .grid-3{ grid-template-columns:1fr; } }

.pill{ display:inline-block; background:#363636; color:#eaeaea; border-radius:999px; padding:.45rem .9rem; margin:.25rem .35rem .35rem 0; font-size:.95rem; }
.cta{ display:inline-block; padding:.9rem 1.15rem; border-radius:12px; font-weight:700; text-decoration:none; }
.cta-primary{ background:var(--accent); color:#0e0a21; }
.cta-ghost{ border:1px solid #444; color:var(--fg); margin-left:.5rem; }

.s1{ background: radial-gradient(1200px 600px at 75% 20%, #2c2655 0%, transparent 60%) var(--bg); }
.s2{ background: radial-gradient(1200px 600px at 20% 10%, #253b59 0%, transparent 60%) var(--bg); }
.s3{ background: radial-gradient(1200px 600px at 80% 80%, #2c4c3b 0%, transparent 60%) var(--bg); }
.s4{ background: radial-gradient(1200px 600px at 20% 80%, #5a2f3b 0%, transparent 60%) var(--bg); }

.underline{ box-shadow: inset 0 -0.5em rgba(155,135,245,.25); display:inline; }
</style>

<div class="snap">

  <!-- HERO -->
  <section class="section s1" id="hero">
    <div class="wrap">
      <div class="kicker">Aman Valera</div>
      <h1>Reimagining the future through the language of data.</h1>
      <h2>I don’t just analyze it — I transform it into insight.</h2>
      <div style="margin-top:1.6rem;">
        <a class="cta cta-primary" href="#services">See Services</a>
        <a class="cta cta-ghost" href="#impact">See Results</a>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="section s2" id="services">
    <div class="wrap">
      <div class="kicker">Services</div>
      <h1>What I deliver.</h1>
      <div class="grid grid-3" style="margin-top:1.1rem;">
        <div class="card">
          <h2>Business Intelligence</h2>
          <p class="lead">Dashboards, SQL data models, and secure pipelines that turn data into clear decisions. Power BI &amp; Looker Studio included.</p>
        </div>
        <div class="card">
          <h2>Predictive Analytics</h2>
          <p class="lead">End-to-end ML systems for forecasting and strategy — including live sports analytics (e.g., IPL win predictions).</p>
        </div>
        <div class="card">
          <h2>Frontier AI Research</h2>
          <p class="lead">Deep Learning, Biologically Inspired Computation, and Agentic AI — an innovation engine to keep solutions future-ready.</p>
        </div>
      </div>
      <div style="margin-top:1rem;">
        <span class="pill">Power BI</span><span class="pill">Looker Studio</span><span class="pill">SQL</span>
        <span class="pill">Python</span><span class="pill">scikit-learn</span><span class="pill">AWS</span>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section s3" id="about">
    <div class="wrap">
      <div class="kicker">Identity</div>
      <h1>I’m a Data Scientist &amp; Machine Learning Engineer.</h1>
      <p class="lead">Expertise in <strong>sports analytics</strong> and <strong>business intelligence</strong> — bridging pipelines, models, and product to deliver clarity.</p>
      <div style="margin-top:1.6rem;">
        <a class="cta cta-primary" href="/projects/">View Projects</a>
        <a class="cta cta-ghost" href="mailto:youremail@example.com">Contact</a>
      </div>
    </div>
  </section>

  <!-- IMPACT -->
  <section class="section s4" id="impact">
    <div class="wrap">
      <div class="kicker">Impact</div>
      <h1>End-to-end systems that ship.</h1>
      <p class="lead">From SQL pipelines and dashboards to predictive ML models — including an <span class="underline"><strong>84% F1</strong> in live IPL match predictions</span>.</p>
      <div style="margin-top:1.6rem;">
        <a class="cta cta-primary" href="/projects/">Explore the work</a>
        <a class="cta cta-ghost" href="#hero">Back to top</a>
      </div>
    </div>
  </section>

  <!-- FOCUS (optional—kept since you wrote it) -->
  <section id="focus">
    <div class="wrap">
      <h1>Focus</h1>
      <p class="lead"><strong>Practical impact today</strong> — analytics pipelines, dashboards, and models that drive decisions.<br>
      <strong>Exploring tomorrow</strong> — agentic approaches, biologically inspired computation, and statistical modeling.</p>
    </div>
  </section>

</div>
