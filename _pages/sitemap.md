---
layout: single
title: "Sitemap"
permalink: /sitemap/
author_profile: true
sitemap: false
---

{% include base_path %}

<div class="card-grid card-grid--2">
  <a class="card card--link" href="{{ base_path }}/"><h3>Home</h3><p>About me and news.</p></a>
  <a class="card card--link" href="{{ base_path }}/publications/"><h3>Publications</h3><p>All papers, newest first.</p></a>
  <a class="card card--link" href="{{ base_path }}/research/"><h3>Research</h3><p>Themes and open-source code.</p></a>
  <a class="card card--link" href="{{ base_path }}/cv/"><h3>CV</h3><p>Experience, education and honors.</p></a>
</div>

## Papers

{% assign pubs = site.publications | sort: "date" | reverse %}
<ul class="timeline">
{% for p in pubs %}
  <li><span class="timeline__date">{{ p.date | date: "%Y" }}</span><div><a href="{{ base_path }}{{ p.url }}">{{ p.title }}</a></div></li>
{% endfor %}
</ul>
