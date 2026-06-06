---
layout: page
title: Home
permalink: /
nav: false
description: Lab of Cancer Biology, Hanyang University.
---

{% include lcb_style.html %}

<div class="lcb-page">
  <section class="lcb-hero lcb-full-bleed">
    <div class="lcb-hero-inner">
      <div>
        <div class="lcb-top-logos">
          <img class="lcb-hanyang-logo" src="{{ '/assets/img/hanyang_logo.png' | relative_url }}" alt="Hanyang University" />
          <img class="lcb-small-logo" src="{{ '/assets/img/lab_logo_wide.png' | relative_url }}" alt="Lab of Cancer Biology" />
        </div>
        <div class="lcb-kicker">Since 2021 · Hanyang University</div>
        <h1 class="lcb-hero-title"><span>Lab of</span><span>Cancer Biology</span></h1>
        <p class="lcb-kr-title">암생물학연구실<br />한양대학교 생명과학과</p>
        <p class="lcb-hero-lead">
          We study how cancer cells adapt, evolve, and acquire resistance<br />
          to anti-cancer therapies in a perspective of translational research.
        </p>
        <div class="lcb-btn-row">
          <a class="lcb-btn primary" href="{{ '/research/' | relative_url }}">Research</a>
          <a class="lcb-btn" href="{{ '/publications/' | relative_url }}">Publications</a>
        </div>
      </div>
      <div class="lcb-visual" aria-label="Lab visual collage">
        <div class="lcb-visual-card lcb-card-main"><img src="{{ '/assets/img/home/lab_group_2025.jpg' | relative_url }}" alt="Lab group" /></div>
        <div class="lcb-visual-card lcb-card-side"><img src="{{ '/assets/img/home/hero_cancer_cell.jpg' | relative_url }}" alt="Cancer cell" /></div>
        <div class="lcb-visual-card lcb-card-bottom"><img src="{{ '/assets/img/projects/sting_myc_immune_evasion.png' | relative_url }}" alt="MYC-STING immune evasion project" /></div>
        <div class="lcb-visual-badge">Cancer therapy resistance<br />Immune evasion · Omics</div>
      </div>
    </div>
  </section>

  <section class="lcb-section">
    <div class="lcb-action-grid">
      <a class="lcb-action-card dark" href="{{ '/research/' | relative_url }}">
        <h3>Research</h3>
        <p>Mechanisms of cancer drug resistance, immune evasion, oncogenic metabolites, and immunotherapy.</p>
        <span class="lcb-arrow">→</span>
      </a>
      <a class="lcb-action-card" href="{{ '/publications/' | relative_url }}">
        <h3>Publications</h3>
        <p>Peer-reviewed research from the Lab of Cancer Biology, listed in reverse chronological order.</p>
        <span class="lcb-arrow">→</span>
      </a>
    </div>
  </section>

  <section class="lcb-section compact">
    <h2 class="lcb-section-title">People</h2>
    <p class="lcb-section-lead">
      We are looking forward to working with someone who is self-motivated and passionate. If you are interested in joining our team as a graduate student, please contact Prof. Lee.
    </p>
    <div class="lcb-action-grid">
      <a class="lcb-action-card" href="{{ '/professor/' | relative_url }}">
        <h3>Professor</h3>
        <p>Kyung-min Lee, PhD · 이경민</p>
        <span class="lcb-arrow">→</span>
      </a>
      <a class="lcb-action-card dark" href="{{ '/members/' | relative_url }}">
        <h3>Lab Members</h3>
        <p>Current members and alumni of the Lab of Cancer Biology.</p>
        <span class="lcb-arrow">→</span>
      </a>
    </div>
  </section>
</div>
