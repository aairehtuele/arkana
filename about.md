---
layout: default
title: About
permalink: /about/
---
<section class="page-head">
  <h1 class="title">About</h1>
  <p class="lede">
    I’m a multidisciplinary researcher and designer working at the intersection of synthetic biology,
    bioengineering and human–computer interaction. I’m interested in how we can engineer biological
    systems to sense, respond and reveal new information, while making scientific tools more intuitive
    and accessible.
  </p>
  <p class="lede">
    My current work spans molecular biosensing, computational protein design, immunoengineering and
    laboratory automation. Across these fields, I move between the molecular and the human scale: from
    engineering DNA- and protein-based systems to exploring how people interact with scientific
    technologies.
  </p>
  <p class="lede">
    My approach is human-centred and inspired by nature. I’m fascinated by the complexity and elegance
    of living systems, and by the possibilities of learning from and engineering them. Nature is often
    where my ideas begin; people are why I pursue them.
  </p>
  <p class="sub">Reach me at <a href="#" class="em" data-u="{{ site.email_user }}" data-d="{{ site.email_domain }}" data-show="1">{{ site.email_user }} [at] {{ site.email_domain }}</a> · {{ site.location }}</p>
  {% assign cvfile = site.static_files | where: "path", "/assets/files/cv.pdf" | first %}{% if cvfile %}<p><a class="button" href="{{ '/assets/files/cv.pdf' | relative_url }}">Download full CV (PDF)</a></p>{% endif %}
</section>

<div class="prose cv" markdown="1">

## Education

**B.S. Information and Interaction Design & B.Eng. Bioconvergence (double major)** — Yonsei University, Underwood International College
Expected February 2027

## Research

**Designer Cells Lab**, Prof. Patrick Han — Yonsei University
November 2024 – present
Synthetic biology and immunoengineering: RNA-based biosensing for accessible diagnostics, computational protein design, and an AI assistant for the wet lab.

**Designing Intelligence Augmentation Group**, Prof. Jean Y. Song — Yonsei University
January 2025 – August 2026
Human–AI interaction in education: how students question and learn with large language models.

**Computational Energy Materials Lab**, Prof. Woosung Jang — Yonsei University
July 2025 – August 2026
DFT studies of biomarker adsorption on 2D materials, and agentic automation of DFT workflows.

## Teaching & community

**Teaching Assistant, How to Grow (Almost) Anything** — Designer Cells Node
August 2025 – present
Coordinating the node, running lab automation, and supporting students through the course.

## Industry

**Data Science Intern** — I-ESG, Seoul
September – December 2023

</div>
