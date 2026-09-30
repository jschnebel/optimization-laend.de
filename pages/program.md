---
layout: page
title: Program
permalink: /program/
hide_description: true
---

<style>
  .schedule-wrapper {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }

  .schedule-day {
    flex: 1;
    min-width: 0;
  }

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
    padding: 0.75rem 1rem;
    text-align: left;
    font-weight: 600;
  }

  .schedule-table td {
    padding: 0.6rem 1rem;
    border-bottom: 1px solid #ddd !important;
  }

  .schedule-table .time {
    white-space: nowrap;
    width: 135px;
    min-width: 135px;
    font-weight: 500;
  }

    .schedule-table td:last-child {
    width: auto;
    word-break: break-word;
  }

  .schedule-table tr.row-talk td {
    background-color: #ffffff !important;
    color: #222 !important;
  }

  .schedule-table tr.row-plenary td {
    background-color: #dce8f7 !important;
    color: #222 !important;
    font-weight: 500;
  }

  .schedule-table tr.row-break td {
    background-color: #f5f5f5 !important;
    color: #888 !important;
    font-style: italic;
  }

  .schedule-note {
    font-size: 0.85rem;
    color: #555;
    margin-bottom: 1.5rem;
    padding: 0.6rem 1rem;
    background: #f0f5ff !important;
    border-left: 3px solid #4a6fa5;
    border-radius: 2px;
  }

.day-heading {
    font-size: 1.1rem;
    font-weight: 700;
    color: #4a6fa5;
    margin-top: 0;
    margin-bottom: 0;
    padding-bottom: 0.3rem;
    height: 3.5rem;
    box-sizing: border-box;
    display: flex;
    align-items: flex-end;
    text-align: left;
    width: 100%;
  }

  @media (max-width: 768px) {
    .schedule-wrapper {
      flex-direction: column;
    }
  }
</style>

<div class="schedule-wrapper">

  <div class="schedule-day">
    <div class="day-heading">Wednesday, November 25</div>
    <table class="schedule-table">
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-break"><td class="time">12:00 – 13:00</td><td>Welcome / Snacks</td></tr>
        <tr class="row-plenary"><td class="time">13:00 – 13:45</td><td>Stefan Ulbrich</td></tr>
        <tr class="row-talk"><td class="time">13:45 – 14:10</td><td>Peter Ochs</td></tr>
        <tr class="row-talk"><td class="time">14:10 – 14:35</td><td>Edouard Pauwels</td></tr>
        <tr class="row-break"><td class="time">14:35 – 15:05</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">15:05 – 15:30</td><td>Silvia Villa</td></tr>
        <tr class="row-talk"><td class="time">15:30 – 15:55</td><td>Pavel Dvurechensky</td></tr>
        <tr class="row-plenary"><td class="time">15:55 – 16:40</td><td>Panagiotis Patrinos</td></tr>
        <tr class="row-break"><td class="time">16:40 – 17:00</td><td>Coffee break</td></tr>
        <tr class="row-plenary"><td class="time">17:00 – 17:45</td><td>Martin Schmidt</td></tr>
        <tr class="row-talk"><td class="time">17:45 – 18:10</td><td>Tristan van Leeuwen</td></tr>
      </tbody>
    </table>
  </div>

  <div class="schedule-day">
    <div class="day-heading">Thursday, November 26</div>
    <table class="schedule-table">
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-plenary"><td class="time">09:00 – 09:45</td><td>Radu Boț</td></tr>
        <tr class="row-talk"><td class="time">09:45 – 10:10</td><td>Behzad Azmi</td></tr>
        <tr class="row-break"><td class="time">10:10 – 10:35</td><td>Coffee break</td></tr>
        <tr class="row-plenary"><td class="time">10:35 – 11:20</td><td>Dirk Lorenz</td></tr>
        <tr class="row-talk"><td class="time">11:20 – 11:45</td><td>Tuomo Valkonen</td></tr>
        <tr class="row-plenary"><td class="time">11:45 – 12:30</td><td>Kristian Bredies</td></tr>
        <tr class="row-break"><td class="time">12:30 – 13:30</td><td>Lunch break</td></tr>
        <tr class="row-plenary"><td class="time">13:30 – 14:15</td><td>Matthias Ehrhardt</td></tr>
        <tr class="row-talk"><td class="time">14:15 – 14:40</td><td>Nelly Pustelnik</td></tr>
        <tr class="row-talk"><td class="time">14:40 – 15:05</td><td>Stefania Petra</td></tr>
        <tr class="row-break"><td class="time">15:05 – 15:30</td><td>Coffee break</td></tr>
        <tr class="row-plenary"><td class="time">15:30 – 16:15</td><td>Michael Hintermüller</td></tr>
        <tr class="row-plenary"><td class="time">16:15 – 17:00</td><td>Barbara Kaltenbacher</td></tr>
        <tr class="row-break"><td class="time">17:00 – 17:10</td><td>Short break</td></tr>
        <tr class="row-break"><td class="time">17:10 – 18:10</td><td>Panel</td></tr>
      </tbody>
    </table>
  </div>

  <div class="schedule-day">
    <div class="day-heading">Friday, November 27</div>
    <table class="schedule-table">
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-talk"><td class="time">08:30 – 08:55</td><td>Jalal Fadili</td></tr>
        <tr class="row-plenary"><td class="time">08:55 – 09:40</td><td>Luca Calatroni</td></tr>
        <tr class="row-talk"><td class="time">09:40 – 10:05</td><td>Markus Haltmeier</td></tr>
        <tr class="row-break"><td class="time">10:05 – 10:30</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">10:30 – 10:55</td><td>Marcello Carioni</td></tr>
        <tr class="row-plenary"><td class="time">10:55 – 11:40</td><td>Bernadette Hahn-Rigaud</td></tr>
        <tr class="row-break"><td class="time">11:40 – 13:10</td><td>Lunch break</td></tr>
        <tr class="row-talk"><td class="time">13:10 – 13:35</td><td>Simon Weißmann</td></tr>
        <tr class="row-plenary"><td class="time">13:35 – 14:20</td><td>Bastian von Harrach</td></tr>
        <tr class="row-plenary"><td class="time">14:20 – 15:05</td><td>Russell Luke</td></tr>
        <tr class="row-break"><td class="time">15:05</td><td>Discussion / Closing</td></tr>
      </tbody>
    </table>
  </div>

</div>