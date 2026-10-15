---
permalink: /
title: "Yiran (Betty) Yuan"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="home-intro">
  <p class="home-kicker">Statistics for trustworthy knowledge</p>
  <p class="home-lead">I am Yiran (Betty) Yuan, a B.S. candidate in Statistics at the Southern University of Science and Technology. My research asks how mathematical structure and careful statistical evaluation can turn complex data and AI outputs into trustworthy evidence.</p>
  <p>My work follows how knowledge emerges and diffuses through citation networks, how biomedical evidence can be retrieved without losing its provenance, and how medical-imaging models respond to signals that are subtle even for experts. I use network science, statistical learning, uncertainty quantification, and auditable evaluation to study these questions.</p>
  <p>What excites me most are the discrepancies that reveal a deeper methodological problem: uneven diffusion of knowledge across cities, an LLM mistaking a regression coefficient for a correlation, or an imaging model responding to a barely visible hemispheric asymmetry. I enjoy solving these puzzles collaboratively and making the resulting analysis transparent enough to question, reproduce, and improve.</p>
  <p>I am currently looking for PhD positions for Fall 2027, especially opportunities at the intersection of statistics, complex networks, and trustworthy AI.</p>
  <div class="home-cta">
    <a class="btn btn--warm" href="{{ '/portfolio/' | relative_url }}">View Research</a>
    <a class="btn btn--warm" href="{{ '/files/Yiran_Yuan_CV.pdf' | relative_url }}">Download CV</a>
    <a class="btn btn--light-outline" href="mailto:{{ site.author.email }}">Email Me</a>
  </div>
</section>

## Research Interests

<section class="research-pillars">
  <article class="research-pillar">
    <h3>Complex Networks &amp; Science of Science</h3>
    <p>Emergence and diffusion of scientific knowledge across citation, institutional, and geographic networks.</p>
  </article>
  <article class="research-pillar">
    <h3>Trustworthy Biomedical AI</h3>
    <p>Calibration, robustness, uncertainty, and statistical evaluation for biomedical evidence and medical imaging.</p>
  </article>
  <article class="research-pillar">
    <h3>Auditable AI-Assisted Inference</h3>
    <p>Measurement error, evidence provenance, and reproducible evaluation of machine-generated scientific variables.</p>
  </article>
</section>

## News

<ul class="home-news">
  <li><strong>September 30, 2026</strong> — Presented <em>Evidence-Oriented Mapping of Subjective–Objective Cognitive Dissociation in HIV and Alzheimer’s Disease</em> at the Penn CFAR Scientific Symposium.</li>
  <li><strong>September 2026</strong> — <em>SymBreak</em> entered review at ICLR 2027.</li>
  <li><strong>2026</strong> — Continuing a working paper on the emergence and diffusion of scientific knowledge.</li>
</ul>

## Featured Research

<section class="featured-projects">
{% assign featured_projects = site.portfolio | where: "featured", true | sort: "order" %}
{% for post in featured_projects %}
  <article class="project-card">
    <div class="project-card-body">
      <p class="project-card-date">{{ post.date_text }}</p>
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <div class="project-card-excerpt">{{ post.excerpt | markdownify }}</div>
      <a class="section-link" href="{{ post.url | relative_url }}">Read project details →</a>
    </div>
  </article>
{% endfor %}
</section>

<p><a class="section-link" href="{{ '/portfolio/' | relative_url }}">Explore all research and additional projects →</a></p>

## Beyond Research

<p class="beyond-research">Outside research, I recharge through travelling, city walks, making coffee and desserts, and dancing. These small rituals keep me curious, observant, and connected to people and places beyond my datasets.</p>

<section class="interest-strip">
  <figure><img loading="lazy" src="{{ '/images/interests/travel.jpg' | relative_url }}" alt="Travelling"><figcaption>Travelling</figcaption></figure>
  <figure><img loading="lazy" src="{{ '/images/interests/citywalk.jpg' | relative_url }}" alt="City walks"><figcaption>City walks</figcaption></figure>
  <figure><img loading="lazy" src="{{ '/images/interests/coffee-desserts.jpg' | relative_url }}" alt="Coffee and desserts"><figcaption>Coffee &amp; desserts</figcaption></figure>
  <figure><img loading="lazy" src="{{ '/images/interests/dancing.jpg' | relative_url }}" alt="Dancing"><figcaption>Dancing</figcaption></figure>
</section>

<p><a class="section-link" href="{{ '/activities/' | relative_url }}">See how I participate in academic communities →</a></p>
