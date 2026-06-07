---
layout: default
title: Home
permalink: /
nav: false
description:
---

{% include lcb_style.html %}
{% include lcb_nav.html %}

<div class="lcb-page lcb-home-page">
  <section class="lcb-home-hero lcb-full-bleed">
    <div class="lcb-home-inner">
      <div class="lcb-hero-copy">
        <div class="lcb-hero-kicker">SINCE 2021 · HANYANG UNIVERSITY</div>
        <h1 class="lcb-hero-title">Lab of Cancer<br />Biology</h1>
        <p class="lcb-hero-kr">암생물학연구실<br />한양대학교 생명과학과</p>
        <div class="lcb-hero-rule"></div>
        <p class="lcb-hero-lead">We study how cancer cells adapt, evolve, and acquire resistance to anti-cancer therapies in a perspective of translational research.</p>
      </div>
    </div>
  </section>

  <section class="lcb-home-quick lcb-full-bleed">
    <div class="lcb-quick-inner">
      <div class="lcb-quick-card">
        <span class="lcb-eyebrow">Research</span>
        <h2>Research &amp; Publications</h2>
        <p>Explore our research topics, previous projects, and publication record.</p>
        <div class="lcb-quick-actions">
          <a href="{{ '/research/' | relative_url }}">Research</a>
          <a href="{{ '/publications/' | relative_url }}">Publications</a>
        </div>
      </div>
      <div class="lcb-quick-card">
        <span class="lcb-eyebrow">People</span>
        <h2>Professor &amp; Members</h2>
        <p>Meet the principal investigator, current members, and alumni.</p>
        <div class="lcb-quick-actions">
          <a href="{{ '/professor/' | relative_url }}">Professor</a>
          <a href="{{ '/members/' | relative_url }}">Members</a>
        </div>
      </div>
    </div>
  </section>

  <section class="lcb-home-gallery lcb-full-bleed">
    <div class="lcb-gallery-head">
      <span class="lcb-eyebrow">Gallery</span>
      <h2>Recent Lab Moments</h2>
    </div>
    <div class="lcb-slider">
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/2025_ksmcb_overview.jpg' | relative_url }}" alt="2025 KSMCB" /><div class="lcb-slide-caption"><strong>2025 KSMCB</strong></div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/2025_ksmcb_son_seunghan.jpg' | relative_url }}" alt="손승한 포스터" /><div class="lcb-slide-caption"><strong>2025 KSMCB</strong><br />Poster by 손승한</div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/2025_ksmcb_jo_dayoung.jpg' | relative_url }}" alt="조다영 포스터" /><div class="lcb-slide-caption"><strong>2025 KSMCB</strong><br />Poster by 조다영</div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/teacher_day_2025.jpg' | relative_url }}" alt="스승의 날" /><div class="lcb-slide-caption"><strong>스승의 날</strong> (2025)</div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/lab_picnic_spring_2024.jpg' | relative_url }}" alt="Lab picnic" /><div class="lcb-slide-caption"><strong>Lab Picnic</strong> (Spring 2024)</div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/dr_shigeri_visit_2024.jpg' | relative_url }}" alt="Dr. Shigeri visit" /><div class="lcb-slide-caption"><strong>Dr. Shigeri Visit</strong> (2024)</div></div>
      <div class="lcb-slide"><img src="{{ '/assets/img/gallery/graduate_lee_taewon_2024.jpg' | relative_url }}" alt="이태원 졸업" /><div class="lcb-slide-caption"><strong>Graduation</strong> - 이태원 (MS 2024)</div></div>
    </div>
  </section>
</div>
