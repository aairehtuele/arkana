---
layout: default
title: About
permalink: /about/
---
<section class="page-head">
  <h1 class="title">About</h1>
  <p class="lede">
    I’m fascinated by the complexity and elegance of living systems, and by the potential to understand,
    learn from, and engineer them. My research interests lie at the intersection of synthetic biology and
    immunoengineering, where I hope to translate our understanding of biological systems into new
    approaches to engineering biological functions.
  </p>
  <p class="sub">Reach me at <a href="#" class="em" data-u="{{ site.email_user }}" data-d="{{ site.email_domain }}" data-show="1">{{ site.email_user }} [at] {{ site.email_domain }}</a> · {{ site.location }}</p>
  {% assign cvfile = site.static_files | where: "path", "/assets/files/cv.pdf" | first %}{% if cvfile %}<p><a class="button" href="{{ '/assets/files/cv.pdf' | relative_url }}">Download full CV (PDF)</a></p>{% endif %}
</section>

<div class="prose cv">

<h2>Education</h2>

<div class="entry">
  <h3>B.S. Information and Interaction Design &amp; B.Eng. Bioconvergence (double major)</h3>
  <p class="where">Yonsei University, Underwood International College · Expected February 2027</p>
</div>

<h2>Research</h2>

<div class="entry">
  <h3>Designer Cells Lab, Prof. Patrick Han</h3>
  <p class="where">Yonsei University · November 2024 – present</p>
</div>

<div class="entry">
  <h3>Designing Intelligence Augmentation Group, Prof. Jean Y. Song</h3>
  <p class="where">Yonsei University · January 2025 – August 2026</p>
</div>

<div class="entry">
  <h3>Computational Energy Materials Lab, Prof. Woosung Jang</h3>
  <p class="where">Yonsei University · July 2025 –</p>
</div>

<h2>Teaching &amp; community</h2>

<div class="entry">
  <h3>Teaching Assistant, How to Grow (Almost) Anything</h3>
  <p class="where">Designer Cells Node · August 2025 – present</p>
</div>

<h2>Industry</h2>

<div class="entry">
  <h3>Data Science Intern</h3>
  <p class="where">I-ESG, Seoul · September – December 2023</p>
</div>

</div>
