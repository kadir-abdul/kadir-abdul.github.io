---
layout: single
title: "Open Master Thesis Topics"
permalink: /thesis/
author_profile: true
---

<p class="hero__lead">I supervise MSc theses at DFKI and the University of Oldenburg on interpretability and reliability of vision–language models. The topics below are open; I'm also happy to discuss your own idea in this area.</p>

<div class="card-grid">
{% for t in site.thesis %}
  <a class="card card--link" href="{{ t.url }}">
    <span class="card__num">Open topic</span>
    <h3>{{ t.title }}</h3>
    <p>{{ t.excerpt | strip_html }}</p>
  </a>
{% endfor %}
</div>

## How to apply

Email <a href="mailto:abdul.kadir@dfki.de">abdul.kadir@dfki.de</a> with your CV, transcript, and a few sentences on which topic interests you and why.
