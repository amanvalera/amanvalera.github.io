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
:root{ --masthead-h:64px; }

.page__inner-wrap>header{ display:none !important; } /* hide big auto title */
.page__content{ padding:0; }

html,body{ height:100%; }
body{
  background:#222; color:#f5f5f5;
  scroll-snap-type:y mandatory;
  scroll-padding-top:var(--masthead-h);
  overscroll-behavior-y:contain;
}

/* Only these sections snap */
#snap-stack>section{
  min-height:calc(100svh - var(--masthead-h));
  min-height:calc(100vh - var(--masthead-h));
  scroll-snap-align:start;
  scroll-snap-stop:always;
  display:flex; align-items:center;
}
.page__footer{ scroll-snap-align:none; }     /* footer won't snap */

.wrap{ max-width:1100px; margin:0 auto; padding:6rem 2rem; }
h1{ font-size:clamp(2.6rem,6vw,5rem); line-height:1.05; margin:0 0 1rem; }
h2{ font-size:clamp(1.4rem,3vw,2rem); color:#bdbdbd; font-weight:600; margin:0; }
.lead{ font-size:clamp(1.1rem,2vw,1.35rem); color:#bdbdbd; max-width:60ch; }

.grid{ display:grid; gap:1.1rem; }
.grid-3{ grid-template-columns:repeat(3,minmax(0,1fr)); }
@media (max-width:900px){ .grid-3{ grid-template-columns:1fr; } }

.card{ background:#2b2b2b; border-radius:20px; padding:1.25rem 1.4rem; box-shadow:0 10px 30px rgba(0,0,0,.25); }
.cta{ display:inline-block; padding:.9rem 1.15rem; border-radius:12px; font-weight:700; text-decoration:none; }
.cta-primary{ background:#9b87f5; color:#0e0a21; }
.cta-ghost{ border:1px solid #444; color:#f5f5f5; margin-left:.5rem; }
.underline{ box-shadow:inset 0 -.5em rgba(155,135,245,.25); display:inline; }

/* gradients */
.s1{ background:radial-gradient(1200px 600px at 75% 20%, #2c2655 0%, transparent 60%) #222; }
.s2{ background:radial-gradient(1200px 600px at 20% 10%, #253b59 0%, transparent 60%) #222; }
.s3{ background:radial-gradient(1200px 600px at 80% 80%, #2c4c3b 0%, transparent 60%) #222; }
.s4{ background:radial-gradient(1200px 600px at 20% 80%, #5a2f3b 0%, transparent 60%) #222; }
</style>

<div id="snap-stack" markdown="0">

  <!-- HERO -->
  <section class="s1" id="hero">
    <div class="wrap">
      <h1>Reimagining the future through the language of data.</h1>
      <h2>I don’t just analyze it — I transform it into insight.</h2>
      <div style="margin-top:1.6rem;">
        <a class="cta cta-primary" href="#services">See Services</a>
        <a class="cta cta-ghost" href="#impact">See Results</a>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section class="s2" id="services">
    <div class="wrap">
      <h1>What I deliver.</h1>
      <div class="grid grid-3" style="margin-top:1.1rem;">
        <div class="card">
          <h2>Business Intelligence</h2>
          <p class="lead">Dashboards, SQL data models, and secure pipelines that turn data into clear decisions (Power BI, Looker Studio).</p>
        </div>
        <div class="card">
          <h2>Predictive Analytics</h2>
          <p class="lead">End-to-end ML systems for forecasting and strategy — including live sports analytics (e.g., IPL win predictions).</p>
        </div>
        <div class="card">
          <h2>Frontier AI Research</h2>
          <p class="lead">Deep Learning, Biologically Inspired Computation, and Agentic AI — keeping solutions future-ready.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="s3" id="about">
    <div class="wrap">
      <h1>I’m a Data Scientist &amp; Machine Learning Engineer.</h1>
      <p class="lead">Expertise in <strong>sports analytics</strong> and <strong>business intelligence</strong> — bridging pipelines, models, and product to deliver clarity.</p>
    </div>
  </section>

  <!-- IMPACT -->
  <section class="s4" id="impact">
    <div class="wrap">
      <h1>End-to-end systems that ship.</h1>
      <p class="lead">
        From SQL pipelines and dashboards to predictive ML models — including an
        <span class="underline"><strong>84% F1</strong> in live IPL match predictions</span>.
      </p>
      <div style="margin-top:1.6rem;">
        <a class="cta cta-primary" href="/projects/">View Projects</a>
        <a class="cta cta-ghost" href="mailto:youremail@example.com">Contact</a>
      </div>
    </div>
  </section>

</div>
