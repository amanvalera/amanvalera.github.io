---
permalink: /
title: "Aman Valera – Data Scientist & AI Innovator"
layout: single
classes: wide
author_profile: true      # keep sidebar
sidebar: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ===== BODY-LEVEL SCROLL SNAP (keep theme chrome) ===== */
:root { --masthead-h: 64px; }                 /* adjust if your top bar is taller */
html { height:100%; scroll-behavior:smooth; }
body {
  height:100%;
  scroll-snap-type:y mandatory;               /* snap on the body */
  scroll-padding-top: var(--masthead-h);      /* anchors land below the masthead */
  background:#222; color:#f5f5f5;
}

/* Make each content section fill the visible space under the fixed masthead */
.page__content > .snap-section {
  min-height: calc(100svh - var(--masthead-h));
  min-height: calc(100vh - var(--masthead-h));
  scroll-snap-align: start;
  scroll-snap-stop: always;                   /* prevents skipping multiple sections */
  display:flex; align-items:center;
}

/* Optional: hide the big auto page title; comment this out if you want it visible */
.page__inner-wrap > header,
.page__title,
.page__meta { display:none !important; }

/* Spacing so sections can touch edges */
.page__content { padding:0; }

/* Typography */
h1{ font-size:clamp(2.6rem,6vw,5rem); line-height:1.05; margin:0 0 1rem; }
h2{ font-size:clamp(1.4rem,3vw,2rem); color:#bdbdbd; font-weight:600; margin:0; }
.lead{ font-size:clamp(1.1rem,2vw,1.35rem); color:#bdbdbd; max-width:60ch; }

/* Cards / grid */
.card{ background:#2b2b2b; border-radius:20px; padding:1.25rem 1.4rem; box-shadow:0 10px 30px rgba(0,0,0,.25); }
.grid{ display:grid; gap:1.1rem; }
.grid-3{ grid-template-columns:repeat(3,minmax(0,1fr)); }
@media (max-width: 900px){ .grid-3{ grid-template-columns:1fr; } }

/* Buttons */
.cta{ display:inline-block; padding:.9rem 1.15rem; border-radius:12px; font-weight:700; text-decoration:none; }
.cta-primary{ background:#9b87f5; color:#0e0a21; }
.cta-ghost{ border:1px solid #444; color:#f5f5f5; margin-left:.5rem; }

/* Subtle gradients per section (optional) */
.s1{ background: radial-gradient(1200px 600px at 75% 20%, #2c2655 0%, transparent 60%) #222; }
.s2{ background: radial-gradient(1200px 600px at 20% 10%, #253b59 0%, transparent 60%) #222; }
.s3{ background: radial-gradient(1200px 600px at 80% 80%, #2c4c3b 0%, transparent 60%) #222; }
.s4{ background: radial-gradient(1200px 600px at 20% 80%, #5a2f3b 0%, transparent 60%) #222; }

.underline{ box-shadow: inset 0 -0.5em rgba(155,135,245,.25); display:inline; }
.wrap{ width:100%; max-width:1100px; margin:0 auto; padding:6rem 2rem; }
</style>

<!-- HERO -->
<section class="snap-section s1" id="hero">
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
<section class="snap-section s2" id="services">
  <div class="wrap">
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
  </div>
</section>

<!-- ABOUT -->
<section class="snap-section s3" id="about">
  <div class="wrap">
    <h1>I’m a Data Scientist &amp; Machine Learning Engineer.</h1>
    <p class="lead">Expertise in <strong>sports analytics</strong> and <strong>business intelligence</strong> — bridging pipelines, models, and product to deliver clarity.</p>
  </div>
</section>

<!-- IMPACT -->
<section class="snap-section s4" id="impact">
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


I focus on two things:  
- **Practical impact today** → building analytics pipelines, dashboards, and models that drive business decisions.  
- **Exploring tomorrow** → researching agent-based approaches to automate and studied Biologically inspired computation and Statistical Modelling.  

---



This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
