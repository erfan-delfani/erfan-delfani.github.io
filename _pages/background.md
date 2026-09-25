---
layout: archive
title: "Background"
permalink: /background/
author_profile: true
---

<style>
  .cv-section-title {
    margin-top: 2.8rem;
    margin-bottom: 1rem;
    font-size: 1.25rem;
    font-weight: bold;
    border-bottom: 2px solid #eaeaea;
    padding-bottom: 0.35rem;
    color: #222;
  }
  .cv-line {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    font-size: 0.92rem;
    line-height: 1.5;
    margin-bottom: 0.4rem;
    color: #333;
  }
  .cv-line strong {
    color: #111;
  }
  .cv-content {
    flex: 1;
    text-align: justify;
    text-justify: inter-word;
    text-align-last: left;
  }
  .cv-date {
    font-size: 0.85rem;
    color: #666;
    white-space: nowrap;
    margin-left: 1.2rem;
  }
  .cv-line a, .cv-expand-item a {
    color: #0366d6;
    text-decoration: none;
  }
  .cv-line a:hover, .cv-expand-item a:hover {
    text-decoration: underline;
  }

  /* Sleek Modern Expandable Items */
  .cv-expand-item {
    margin-bottom: 0.6rem;
  }
  .cv-summary {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 0.92rem;
    line-height: 1.5;
    cursor: pointer;
    list-style: none;
    user-select: none;
  }
  .cv-summary::-webkit-details-marker {
    display: none;
  }
  .cv-summary-left {
    display: flex;
    align-items: center;
    gap: 9px;
  }

  /* Elegant Geometric +/- Badge */
  .cv-toggle-btn {
    position: relative;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 17px;
    height: 17px;
    border-radius: 4px;
    background-color: #f3f4f6;
    border: 1px solid #c7cbd1;
    flex-shrink: 0;
    transition: all 0.2s ease;
  }
  /* Horizontal bar */
  .cv-toggle-btn::before {
    content: "";
    position: absolute;
    width: 9px;
    height: 1.8px;
    background-color: #4b5563;
    border-radius: 1px;
    transition: background-color 0.2s ease;
  }
  /* Vertical bar */
  .cv-toggle-btn::after {
    content: "";
    position: absolute;
    width: 1.8px;
    height: 9px;
    background-color: #4b5563;
    border-radius: 1px;
    transition: transform 0.25s ease, opacity 0.2s ease, background-color 0.2s ease;
  }

  /* Hover & Open States */
  .cv-expand-item:hover .cv-toggle-btn {
    background-color: #e8f0fe;
    border-color: #1a73e8;
  }
  .cv-expand-item:hover .cv-toggle-btn::before,
  .cv-expand-item:hover .cv-toggle-btn::after {
    background-color: #1a73e8;
  }
  details[open] .cv-toggle-btn {
    background-color: #e8f0fe;
    border-color: #1a73e8;
  }
  details[open] .cv-toggle-btn::before {
    background-color: #1a73e8;
  }
  details[open] .cv-toggle-btn::after {
    transform: rotate(90deg);
    opacity: 0;
  }

  .cv-desc {
    padding-left: 26px;
    font-size: 0.77rem;
    color: #555;
    line-height: 1.45;
    margin-top: 0.3rem;
    margin-bottom: 0.4rem;
  }
</style>

<h2 class="cv-section-title" style="margin-top: 0.8rem;">Education</h2>

<div class="cv-line">
  <span class="cv-content"><strong>Ph.D. Candidate in Computer and Information Science</strong>, <a href="https://liu.se/en" target="_blank" rel="noopener noreferrer">Linköping University</a>, Linköping, Sweden</span>
  <span class="cv-date">2024 – Present</span>
</div>

<div class="cv-line">
  <span class="cv-content"><strong>M.Sc. in Telecommunication Systems</strong>, Sharif University of Technology, Tehran, Iran</span>
  <span class="cv-date">2012 – 2014</span>
</div>

<div class="cv-line">
  <span class="cv-content"><strong>B.Sc. in Electrical Engineering (Electronics)</strong>, Razi University, Kermanshah, Iran</span>
  <span class="cv-date">2008 – 2012</span>
</div>

<h2 class="cv-section-title">Visiting Positions</h2>

<details class="cv-expand-item">
  <summary class="cv-summary">
    <span class="cv-summary-left">
      <span class="cv-toggle-btn"></span>
      <span><strong>Industrial Secondment</strong>, <a href="https://mcs-datalabs.com/" target="_blank" rel="noopener noreferrer">MCS Data Labs</a>, Berlin, Germany</span>
    </span>
    <span class="cv-date">Jul. 2026 – Oct. 2026</span>
  </summary>
  <div class="cv-desc">
    Energy-efficient data management for IoMT wearables under the EU MSCA <a href="https://elixirion-mc.eu/" target="_blank" rel="noopener noreferrer">ELIXIRION</a> Project (hosted by Dr. A. Schramm & Mr. F. Mousa).
  </div>
</details>

<details class="cv-expand-item">
  <summary class="cv-summary">
    <span class="cv-summary-left">
      <span class="cv-toggle-btn"></span>
      <span><strong>Industrial Secondment</strong>, <a href="https://www.orange.pl/" target="_blank" rel="noopener noreferrer">Orange Polska</a>, Warsaw, Poland</span>
    </span>
    <span class="cv-date">Jan. 2026 – Apr. 2026</span>
  </summary>
  <div class="cv-desc">
    Network management and resource allocation in telecom networks under the EU MSCA <a href="https://elixirion-mc.eu/" target="_blank" rel="noopener noreferrer">ELIXIRION</a> Project (hosted by Dr. L. Tomaszewski).
  </div>
</details>

<details class="cv-expand-item">
  <summary class="cv-summary">
    <span class="cv-summary-left">
      <span class="cv-toggle-btn"></span>
      <span><strong>Research Engineer</strong>, <a href="https://liu.se/en" target="_blank" rel="noopener noreferrer">Linköping University</a>, Linköping, Sweden</span>
    </span>
    <span class="cv-date">Aug. 2023 – Feb. 2024</span>
  </summary>
  <div class="cv-desc">
    Semantics-aware communication for energy-efficient TN/NTN networks under the EU <a href="https://ether-project.eu/" target="_blank" rel="noopener noreferrer">ETHER</a> Project (hosted by Prof. N. Pappas).
  </div>
</details>
