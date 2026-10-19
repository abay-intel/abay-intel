---
---

<section class="hero">
  <div>
    <h1>Groundwater intelligence for the Abay Basin</h1>
    <p>YeAbay Wuha Intel is a 24-month applied research initiative led by the Blue Nile Water Institute at Bahir Dar University. It builds an AI-enabled, GPS-based platform that helps water officers and planners decide where to drill and how much groundwater can be sustained.</p>
  </div>

  <figure class="strata">
    <svg viewBox="0 0 600 440" role="img" aria-labelledby="strata-title">
      <title id="strata-title">Cross-section of a highland aquifer with a water table and a monitored well</title>
      <rect width="600" height="440" style="fill: var(--background-alt)" />
      <path d="M0 150 C150 130 300 170 450 150 S600 135 600 150 L600 440 L0 440 Z" fill="#5d9aa6" />
      <path d="M0 230 C150 210 300 250 450 230 S600 215 600 230 L600 440 L0 440 Z" fill="#2f6f7e" />
      <path d="M0 310 C150 290 300 330 450 310 S600 295 600 310 L600 440 L0 440 Z" fill="#1d5764" />
      <path d="M0 380 C150 365 300 395 450 380 S600 368 600 380 L600 440 L0 440 Z" fill="#123f4b" />
      <path class="water-table" pathLength="100" d="M0 200 C150 185 300 215 450 195 S600 182 600 198" fill="none" stroke="#7fc4d0" stroke-width="4" />
      <rect x="420" y="112" width="14" height="250" fill="none" stroke="#b9772b" stroke-width="3" />
      <rect x="423" y="200" width="8" height="158" fill="#7fc4d0" opacity="0.8" />
    </svg>
  </figure>
</section>

{% include section.html %}

## Highlights

{% capture text %}

We combine satellite observations, aquifer testing, and machine learning to map groundwater potential and estimate sustainable yield.

{%
  include button.html
  link="research"
  text="See our research"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/strata.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

The project builds a spatial groundwater database, an AI model, a groundwater flow model, and a web application, followed by field validation.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/sites.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

A core technical team from Bahir Dar University and the Blue Nile Water Institute, with co-investigators in Rwanda and Finland, leads the work.

{%
  include button.html
  link="team"
  text="Meet our team"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/flow.jpg"
  link="team"
  title="Our Team"
  text=text
%}
