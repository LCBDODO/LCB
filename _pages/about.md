---
layout: page
title: Home
permalink: /
nav: true
nav_order: 1
description: Home of the Lab of Cancer Biology at Hanyang University.
---

{% include lcb_style.html %}


<div class="lcb-page">
  <section class="lcb-hero">
    <div>
      <div class="lcb-logo-wrap">
        <img src="{{ '/assets/img/lab_logo.png' | relative_url }}" alt="Lab logo" class="lcb-logo-img" onerror="this.onerror=null;this.src='{{ '/assets/img/lab_logo.svg' | relative_url }}';" />
      </div>
      <div class="lcb-kicker">Since 2021</div>
      <h1 class="lcb-title"><strong>Lab of Cancer Biology</strong></h1>
      <p class="lcb-subtitle"><strong>암생물학연구실</strong><br>한양대학교 생명과학과</p>
      <p class="lcb-subtitle">We study how cancer cells adapt, evolve, and acquire resistance to anti-cancer therapies in a perspective of translational research.</p>
      <div class="lcb-button-row">
        <a class="lcb-button" href="{{ '/research/' | relative_url }}">Research</a>
        <a class="lcb-button" href="{{ '/publications/' | relative_url }}">Publications</a>
        <a class="lcb-button" href="{{ '/members/' | relative_url }}">Members</a>
        <a class="lcb-button" href="{{ '/contact/' | relative_url }}">Contact</a>
      </div>
    </div>
    <div>
      <img src="{{ '/assets/img/home_hero.gif' | relative_url }}" alt="Cancer biology" class="lcb-hero-img" onerror="this.onerror=null;this.src='{{ '/assets/img/home_hero.jpg' | relative_url }}';" />
    </div>
  </section>

  <section class="lcb-section">
    <h2 class="lcb-rule-title">Research</h2>
    <p>We are wholly dedicated to acquiring a better understanding of the mechanisms of cancer drug resistance in order to vastly improve patient survival and quality of life.</p>
  </section>

  <section class="lcb-section">
    <h2 class="lcb-rule-title">People</h2>
    <p>We are looking forward to working with someone who is self-motivated and passionate. If you are interested in joining our team as a graduate student, please feel free to contact Prof. Lee.</p>
  </section>
</div>
