---
layout: default
title: About
permalink: /about/
---
<section class="page-head">
  <p class="eyebrow">01 — About</p>
  <h1 class="title">About</h1>
  <p class="lede">A few sentences about who you are, what you work on and what you care about. <em>(Replace this.)</em></p>
  <p class="intro">Reach me at <a href="mailto:{{ site.email }}">{{ site.email }}</a> · {{ site.location }}</p>
  {% assign cvfile = site.static_files | where: "path", "/assets/files/cv.pdf" | first %}{% if cvfile %}<p><a class="button" href="{{ '/assets/files/cv.pdf' | relative_url }}">Download full CV (PDF)</a></p>{% endif %}
</section>

<div class="prose cv" markdown="1">

## Education

**MSc, Your Programme** — University Name
2025 – present

**BSc, Your Degree** — University Name
2021 – 2025

## Experience

**Research Intern** — Lab Name, Institute
2025 – present
One line on what you do there.

## Skills

Molecular cloning · Cell culture · Python · Illustration

## Awards

**Award name** — Awarding body, 2024

</div>
