---
layout: page
title: Projects
permalink: /projects/
description: Research and engineering work across LLMs, deep learning, and software systems.
nav: true
nav_order: 1
portfolio: true
---

<div class="portfolio-projects">
  <section class="portfolio-section" aria-labelledby="research-heading">
    <div class="section-heading">
      <p class="section-eyebrow">01 / Research</p>
      <h2 id="research-heading">AI &amp; Research</h2>
    </div>
    <div class="timeline-list">
      {% assign research_projects = site.data.portfolio_projects | where: 'category', 'research' %}
      {% for item in research_projects %}
        {% include portfolio_item.liquid item=item %}
      {% endfor %}
    </div>
  </section>

  <section class="portfolio-section" aria-labelledby="software-heading">
    <div class="section-heading">
      <p class="section-eyebrow">02 / Engineering</p>
      <h2 id="software-heading">Software</h2>
    </div>
    <div class="timeline-list">
      {% assign software_projects = site.data.portfolio_projects | where: 'category', 'software' %}
      {% for item in software_projects %}
        {% include portfolio_item.liquid item=item %}
      {% endfor %}
    </div>
  </section>
</div>
