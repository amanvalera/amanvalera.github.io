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
  
/* Sidebar default (desktop = fixed)*/
.sidebar {
  position: fixed !important;
  top: var(--masthead-height, 3.5rem);
  left: var(--masthead-height, 3.5rem);
  width: var(--sidebar-width, 300px);
  height: calc(100vh - var(--masthead-height, 3.5rem));
  overflow-y: auto;
  z-index: 100 !important; /* raise above snap-container */
  overflow: visible !important;
}
.sidebar .dropdown,
.sidebar .dropdown * { overflow: visible !important; } 

/* Override body padding-bottom (remove 9em gap) */
body { padding-bottom: 0 !important; }

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
.content-wrap p, 
.content-wrap ul {
  font-size: 1rem;
  line-height: 1.6;
  color: #ddd;
}
.content-wrap ul {
  list-style: disc;
  padding-left: 1.5rem;
  margin: 1rem 0;
}
.content-wrap li { margin: 0.5rem 0; }

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
.hero             { background: radial-gradient(circle at 75% 20%, #2c2655 0%, transparent 70%) #111; }
.services         { background: radial-gradient(circle at 20% 10%, #253b59 0%, transparent 70%) #111; }
.identity-section { background: radial-gradient(circle at 80% 80%, #2c4c3b 0%, transparent 70%) #111; }
.impact           { background: radial-gradient(circle at 20% 80%, #5a2f3b 0%, transparent 70%) #111; }
.focus            { background: #111; }
.about-personal   { background: radial-gradient(circle at 50% 80%, #4b2c5a 0%, transparent 70%) #111; }

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

/* Kill empty meta block */
.page__meta { display: none !important; }

/* Footer */
.page__footer { margin: 0 !important; padding: 0 !important; }
footer.site-footer {
  min-height: auto;
  scroll-snap-align: none !important;
  background: #111;
  color: #f5f5f5;
  margin: 0 !important;
  padding: 2rem;
}

/* Grid for services */
.grid { display: grid; gap: 1.5rem; }
.grid-3 { grid-template-columns: repeat(3, 1fr); }
@media (max-width: 900px) { .grid-3 { grid-template-columns: 1fr; } }

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
  margin: 0 0 0.75rem 0;
  font-size: 1.4rem;
  color: #fff;
}
.card p { margin: 0; color: #ccc; }
</style>

<div class="snap-container">

<!-- HERO -->
<section class="snap-section hero" id="hero">
  <div class="content-wrap">
    <div class="kicker">AMAN VALERA</div>
    <h1>Reimagining the future through the language of data.</h1>
    <h2>I don't just analyse data. I weaponize it into insights.</h2>
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
    <h1>What I Work On</h1>
    <div class="grid grid-3" style="margin-top:1.5rem;">
      <div class="card">
        <h2>Business Intelligence</h2>
        <p>Dashboards and SQL pipelines for real-time analysis. Power BI and Looker Studio supported.</p>
      </div>
      <div class="card">
        <h2>Predictive Analytics and Statistical Modelling</h2>
        <p>Machine learning for forecasting and strategy - applied across business and sport.</p>
      </div>
      <div class="card">
        <h2>AI Research</h2>
        <p>Exploring agentic systems, deep learning, and biologically inspired methods to shape what comes next.</p>
      </div>
    </div>
    <div style="margin-top:1rem;">
      <span class="pill">Power BI</span><span class="pill">Looker Studio</span><span class="pill">SQL</span>
      <span class="pill">Python</span><span class="pill">n8n</span>
    </div>
  </div>
</section>

<!-- IDENTITY (professional about) -->
<section class="snap-section identity-section" id="identity">
  <div class="content-wrap">
    <div class="kicker">Identity</div>
    <h1>Clarity from data</h1>
    <p>I work across <strong>sports analytics</strong> and <strong>business intelligence</strong>. 
       From pipelines to models to dashboards, I connect every layer into systems that support decisions.</p>
  </div>
</section>

<!-- IMPACT -->
<section class="snap-section impact" id="impact">
  <div class="content-wrap">
    <div class="kicker">Impact</div>
    <h1>Results</h1>
    <ul>
      <li>Delivered production SQL pipelines and executive dashboards.</li>
      <li>Built predictive models achieving <strong>84% F1</strong> in live IPL match outcomes.</li>
      <li>Applied research methods directly in working systems, not just prototypes.</li>
    </ul>
    <div style="margin-top:1.6rem;">
      <a class="cta cta-primary" href="/projects/">Explore Projects</a>
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
       <strong>Next:</strong> automated and agentic systems expanding how decisions are made.</p>
  </div>
</section>

<!-- ABOUT ME (personal story, last section) -->
<section class="snap-section about-personal" id="about-me">
  <div class="content-wrap">
    <div class="kicker">About Me</div>
    <h1>A curious builder</h1>
    <p>
      I’m Aman Valera. My background is in <strong>Data Science</strong> and <strong>Machine Learning</strong>,  
      but what drives me is curiosity. I like asking not just <em>what happened</em>,  
      but <em>why it happened</em> - and <em>what might happen next</em>.  
      <br><br>
      That curiosity took me from designing BI dashboards to building predictive systems in <strong>sports analytics</strong>.  
      Cricket, in particular, has been a space where I’ve combined passion with data - forecasting match outcomes, modeling momentum shifts, and showing how data can tell the story of a game.  
      <br><br>
      Beyond sport, I explore how AI can mirror the complexity of nature, and how abstract models can be turned into practical tools.  
      I see myself as a builder: someone who connects pipelines, models, and decisions into systems people can actually use in order to solve their problems.
    </p>
  </div>
</section>

</div>
