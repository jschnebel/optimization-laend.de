---
layout: page
title: Program
permalink: /program/
hide_description: true
---

<style>
  /* ---------- shared table reset (overrides theme table styles) ---------- */
  .schedule-table,
  .schedule-table tbody,
  .schedule-table thead,
  .schedule-table tr,
  .schedule-table td,
  .schedule-table th {
    background: none;
    border: none;
    color: inherit;
  }

  .schedule-table {
    display: table !important;
    width: 100%;
    border-collapse: collapse;
    font-size: 0.9rem;
    margin-bottom: 2rem;
    table-layout: fixed;
    border-top: 2px solid #4a6fa5;
  }

  .schedule-table th {
    background-color: #4a6fa5 !important;
    color: #fff !important;
    padding: 0.6rem 1rem;
    text-align: left;
    font-weight: 600;
  }

  .schedule-table td {
    padding: 0.55rem 1rem;
    border-bottom: 1px solid #ddd !important;
    vertical-align: top;
    line-height: 1.45;
  }

  .schedule-table td.time {
    white-space: nowrap;
    font-weight: 500;
    font-variant-numeric: tabular-nums;
  }

  .schedule-table tr.row-talk td {
    background-color: #ffffff !important;
    color: #222 !important;
  }

  .schedule-table tr.row-plenary td {
    background-color: #dce8f7 !important;
    color: #222 !important;
  }

  .schedule-table tr.row-break td {
    background-color: #f5f5f5 !important;
    color: #888 !important;
    font-style: italic;
  }

  .schedule-table tr.row-event td {
    background-color: #eef3fa !important;
    color: #222 !important;
    font-weight: 600;
  }

  .schedule-table tr.row-block td {
    background-color: #dce8f7 !important;
    color: #222 !important;
    font-weight: 500;
  }

  .day-heading {
    font-size: 1.1rem;
    font-weight: 700;
    color: #4a6fa5;
    margin: 0 0 0.3rem 0;
  }

  .day-room {
    font-size: 0.85rem;
    color: #777;
    margin: -0.2rem 0 0.5rem 0;
  }

  .program-section-title {
    color: #4a6fa5;
    font-size: 1.25rem;
    border-bottom: 2px solid #4a6fa5;
    padding-bottom: 0.3rem;
    margin: 2.5rem 0 1.2rem 0;
  }

  .program-legend {
    font-size: 0.85rem;
    color: #555;
    margin: -0.6rem 0 1.4rem 0;
  }

  .legend-swatch {
    display: inline-block;
    width: 0.9rem;
    height: 0.9rem;
    vertical-align: -0.12rem;
    margin-right: 0.35rem;
    border: 1px solid #c7d6ea;
    background: #dce8f7;
  }

  .download-button {
    display: inline-block;
    padding: 0.6rem 1.2rem;
    background-color: #003056;
    color: #fff !important;
    border-radius: 4px;
    text-decoration: none !important;
    font-weight: 600;
    border-bottom: none !important;
  }

  /* ---------- short program: three days side by side ---------- */
  .schedule-wrapper {
    display: flex;
    gap: 1.5rem;
    align-items: flex-start;
  }

  .schedule-wrapper .schedule-day {
    flex: 1;
    min-width: 0;
  }

  /* theme lets tables bleed 1rem left; keep the small tables inside their column */
  .schedule-table.short-table {
    margin-left: 0 !important;
    margin-right: 0 !important;
  }
  .short-table { font-size: 0.85rem; }
  .short-table th, .short-table td { padding-left: 0.65rem; padding-right: 0.65rem; }
  .short-table col.col-time { width: 6.8rem; }

  /* ---------- detailed program: days stacked vertically ---------- */
  /* full-width tables bleed 1rem on both sides so cell text lines up with the page text */
  .schedule-table.long-table {
    width: calc(100% + 2rem) !important;
    margin-left: -1rem;
    margin-right: -1rem;
  }
  .long-table col.col-time    { width: 8rem; }
  .long-table col.col-speaker { width: 12.5rem; }
  .long-table col.col-title   { width: auto; }

  .long-table td.speaker { font-weight: 600; }
  .long-table td.tba     { color: #999 !important; font-style: italic; }

  @media (max-width: 1100px) {
    .schedule-wrapper { flex-direction: column; gap: 0; align-items: stretch; }
  }

  /* on phones the detailed table becomes: time | speaker / title stacked */
  @media (max-width: 640px) {
    .long-table thead { display: none; }
    .long-table colgroup { display: none; }
    .long-table, .long-table tbody { display: block; width: 100%; }
    .long-table tr {
      display: grid;
      grid-template-columns: 7rem 1fr;
      border-bottom: 1px solid #ddd;
    }
    .long-table td { border-bottom: none !important; padding: 0.45rem 0.6rem; }
    .long-table td.time   { grid-row: 1 / span 2; font-size: 0.85rem; }
    .long-table tr.row-break td.time,
    .long-table tr.row-event td.time { grid-row: auto; }
    .long-table td.speaker { padding-bottom: 0.1rem; }
    .long-table td.title  { grid-column: 2; padding-top: 0.1rem; }
    .long-table tr.row-break td[colspan],
    .long-table tr.row-event td[colspan] { grid-column: 2; }
  }
</style>

All talks take place in Mannheim; see the [venue page]({{ site.baseurl }}/venue/) for the rooms.
Abstracts of all talks are collected in the Book of Abstracts.

<div style="margin: 1.2rem 0 0.5rem 0;">
  <a class="download-button" href="{{ site.baseurl }}/assets/OptiLaend_Book_of_Abstracts.pdf" download>
    &#11015; Download Book of Abstracts (PDF)
  </a>
</div>

<!-- ===================================================================== -->
<!--  PROGRAM AT A GLANCE                                                   -->
<!-- ===================================================================== -->

<h2 class="program-section-title">Program at a glance</h2>

<div class="schedule-wrapper">

  <div class="schedule-day">
    <div class="day-heading">Wednesday, November 25</div>
    <table class="schedule-table short-table">
      <colgroup><col class="col-time"><col></colgroup>
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-break"><td class="time">12:00 – 13:00</td><td>Welcome / Snacks</td></tr>
        <tr class="row-block"><td class="time">13:00 – 14:35</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">14:35 – 15:05</td><td>Coffee break</td></tr>
        <tr class="row-block"><td class="time">15:05 – 16:40</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">16:40 – 17:00</td><td>Coffee break</td></tr>
        <tr class="row-block"><td class="time">17:00 – 18:10</td><td>Talks</td></tr>
      </tbody>
    </table>
  </div>

  <div class="schedule-day">
    <div class="day-heading">Thursday, November 26</div>
    <table class="schedule-table short-table">
      <colgroup><col class="col-time"><col></colgroup>
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-block"><td class="time">09:00 – 10:10</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">10:10 – 10:35</td><td>Coffee break</td></tr>
        <tr class="row-block"><td class="time">10:35 – 12:30</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">12:30 – 13:30</td><td>Lunch break</td></tr>
        <tr class="row-block"><td class="time">13:30 – 15:05</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">15:05 – 15:30</td><td>Coffee break</td></tr>
        <tr class="row-block"><td class="time">15:30 – 17:00</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">17:00 – 17:10</td><td>Short break</td></tr>
        <tr class="row-event"><td class="time">17:10 – 18:10</td><td>Panel</td></tr>
      </tbody>
    </table>
  </div>

  <div class="schedule-day">
    <div class="day-heading">Friday, November 27</div>
    <table class="schedule-table short-table">
      <colgroup><col class="col-time"><col></colgroup>
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-block"><td class="time">08:30 – 10:05</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">10:05 – 10:30</td><td>Coffee break</td></tr>
        <tr class="row-block"><td class="time">10:30 – 11:40</td><td>Talks</td></tr>
        <tr class="row-break"><td class="time">11:40 – 13:10</td><td>Lunch break</td></tr>
        <tr class="row-block"><td class="time">13:10 – 15:05</td><td>Talks</td></tr>
        <tr class="row-event"><td class="time">from 15:05</td><td>Discussion / Closing</td></tr>
      </tbody>
    </table>
  </div>

</div>

<!-- ===================================================================== -->
<!--  DETAILED PROGRAM                                                      -->
<!-- ===================================================================== -->

<h2 class="program-section-title">Detailed program</h2>

<p class="program-legend"><span class="legend-swatch"></span>45-minute plenary talk &nbsp;·&nbsp; all other talks are 25 minutes</p>

<div class="day-heading">Wednesday, November 25</div>
<p class="day-room">Room 008.1, B6 30–32</p>
<table class="schedule-table long-table">
  <colgroup><col class="col-time"><col class="col-speaker"><col class="col-title"></colgroup>
  <thead>
    <tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
  </thead>
  <tbody>
    <tr class="row-break"><td class="time">12:00 – 13:00</td><td colspan="2">Welcome / Snacks</td></tr>
    <tr class="row-plenary"><td class="time">13:00 – 13:45</td><td class="speaker">Stefan Ulbrich</td><td class="title">Adjoint-based Methods for Optimal Control of Hyperbolic Systems of Conservation Laws</td></tr>
    <tr class="row-talk"><td class="time">13:45 – 14:10</td><td class="speaker">Peter Ochs</td><td class="title">Learning Optimization Algorithms with Average Case Convergence Rates</td></tr>
    <tr class="row-talk"><td class="time">14:10 – 14:35</td><td class="speaker">Edouard Pauwels</td><td class="title">Estimation of Monge Transport Maps with Empirical Brenier Potentials</td></tr>
    <tr class="row-break"><td class="time">14:35 – 15:05</td><td colspan="2">Coffee break</td></tr>
    <tr class="row-talk"><td class="time">15:05 – 15:30</td><td class="speaker">Silvia Villa</td><td class="title tba">TBA</td></tr>
    <tr class="row-talk"><td class="time">15:30 – 15:55</td><td class="speaker">Pavel Dvurechensky</td><td class="title">Semismooth Newton Methods with Global Convergence Rates</td></tr>
    <tr class="row-plenary"><td class="time">15:55 – 16:40</td><td class="speaker">Panagiotis Patrinos</td><td class="title tba">TBA</td></tr>
    <tr class="row-break"><td class="time">16:40 – 17:00</td><td colspan="2">Coffee break</td></tr>
    <tr class="row-plenary"><td class="time">17:00 – 17:45</td><td class="speaker">Martin Schmidt</td><td class="title">Calmness of the Solution-Set Mapping for Linear Bilevel and Pricing Problems</td></tr>
    <tr class="row-talk"><td class="time">17:45 – 18:10</td><td class="speaker">Tristan van Leeuwen</td><td class="title">An Invertible Generative Model for Forward and Inverse Problems</td></tr>
  </tbody>
</table>

<div class="day-heading">Thursday, November 26</div>
<p class="day-room">Fuchs-Festsaal (O 138), Mannheim Palace</p>
<table class="schedule-table long-table">
  <colgroup><col class="col-time"><col class="col-speaker"><col class="col-title"></colgroup>
  <thead>
    <tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
  </thead>
  <tbody>
    <tr class="row-plenary"><td class="time">09:00 – 09:45</td><td class="speaker">Radu Boț</td><td class="title">On the Interplay Between Continuous- and Discrete-Time Methods in Convex Optimization and Monotone Inclusions</td></tr>
    <tr class="row-talk"><td class="time">09:45 – 10:10</td><td class="speaker">Behzad Azmi</td><td class="title">Inexact Interior-Point Proximal Methods for Cone-Constrained Nonsmooth Optimization</td></tr>
    <tr class="row-break"><td class="time">10:10 – 10:35</td><td colspan="2">Coffee break</td></tr>
    <tr class="row-plenary"><td class="time">10:35 – 11:20</td><td class="speaker">Dirk Lorenz</td><td class="title">How to Make (Bregman-)Kaczmarz Methods Fast</td></tr>
    <tr class="row-talk"><td class="time">11:20 – 11:45</td><td class="speaker">Tuomo Valkonen</td><td class="title">Point Source Localisation with Unbalanced Optimal Transport</td></tr>
    <tr class="row-plenary"><td class="time">11:45 – 12:30</td><td class="speaker">Kristian Bredies</td><td class="title tba">TBA</td></tr>
    <tr class="row-break"><td class="time">12:30 – 13:30</td><td colspan="2">Lunch break</td></tr>
    <tr class="row-plenary"><td class="time">13:30 – 14:15</td><td class="speaker">Matthias Ehrhardt</td><td class="title tba">TBA</td></tr>
    <tr class="row-talk"><td class="time">14:15 – 14:40</td><td class="speaker">Nelly Pustelnik</td><td class="title">Adaptive Block-Coordinate Forward-Backward: Particular Case of Multilevel Block Strategy for Image Reconstruction</td></tr>
    <tr class="row-talk"><td class="time">14:40 – 15:05</td><td class="speaker">Stefania Petra</td><td class="title tba">TBA</td></tr>
    <tr class="row-break"><td class="time">15:05 – 15:30</td><td colspan="2">Coffee break</td></tr>
    <tr class="row-plenary"><td class="time">15:30 – 16:15</td><td class="speaker">Michael Hintermüller</td><td class="title tba">TBA</td></tr>
    <tr class="row-plenary"><td class="time">16:15 – 17:00</td><td class="speaker">Barbara Kaltenbacher</td><td class="title">Locally-Averaged McCormick Relaxations for Discretization-Regularized Inverse Problems</td></tr>
    <tr class="row-break"><td class="time">17:00 – 17:10</td><td colspan="2">Short break</td></tr>
    <tr class="row-event"><td class="time">17:10 – 18:10</td><td colspan="2">Panel</td></tr>
  </tbody>
</table>

<div class="day-heading">Friday, November 27</div>
<p class="day-room">Fuchs-Festsaal (O 138), Mannheim Palace</p>
<table class="schedule-table long-table">
  <colgroup><col class="col-time"><col class="col-speaker"><col class="col-title"></colgroup>
  <thead>
    <tr><th>Time</th><th>Speaker</th><th>Title</th></tr>
  </thead>
  <tbody>
    <tr class="row-talk"><td class="time">08:30 – 08:55</td><td class="speaker">Anton Schiela</td><td class="title tba">TBA</td></tr>
    <tr class="row-plenary"><td class="time">08:55 – 09:40</td><td class="speaker">Luca Calatroni</td><td class="title">Algorithmic Differentiation for Bilevel Problems with Non-Unique Lower-Level Solutions</td></tr>
    <tr class="row-talk"><td class="time">09:40 – 10:05</td><td class="speaker">Markus Haltmeier</td><td class="title">Locally-Supervised Global Image Reconstruction</td></tr>
    <tr class="row-break"><td class="time">10:05 – 10:30</td><td colspan="2">Coffee break</td></tr>
    <tr class="row-talk"><td class="time">10:30 – 10:55</td><td class="speaker">Marcello Carioni</td><td class="title">Atomic Gradient Flows: Gradient Flows on Sparse Representations</td></tr>
    <tr class="row-plenary"><td class="time">10:55 – 11:40</td><td class="speaker">Bernadette Hahn-Rigaud</td><td class="title tba">TBA</td></tr>
    <tr class="row-break"><td class="time">11:40 – 13:10</td><td colspan="2">Lunch break</td></tr>
    <tr class="row-talk"><td class="time">13:10 – 13:35</td><td class="speaker">Simon Weißmann</td><td class="title">Derivative-Free Bilevel Learning for Inverse Problems: From Stochastic Gradient Estimation to Multilevel Methods</td></tr>
    <tr class="row-plenary"><td class="time">13:35 – 14:20</td><td class="speaker">Bastian von Harrach</td><td class="title">From Inverse Problems in PDEs to Convex Semidefinite Optimization</td></tr>
    <tr class="row-plenary"><td class="time">14:20 – 15:05</td><td class="speaker">Russell Luke</td><td class="title">Quantitative Convergence of Proximal Splitting Iterations in Uniformly Convex Metric Spaces</td></tr>
    <tr class="row-event"><td class="time">from 15:05</td><td colspan="2">Discussion / Closing</td></tr>
  </tbody>
</table>
