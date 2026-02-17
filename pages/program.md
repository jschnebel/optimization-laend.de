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
    width: 120px;
    font-weight: 500;
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
    margin-bottom: 0.5rem;
    padding-bottom: 0.3rem;
    border-bottom: 2px solid #4a6fa5;
  }

  /* Stack on small screens */
  @media (max-width: 768px) {
    .schedule-wrapper {
      flex-direction: column;
    }
  }
</style>



<div class="schedule-wrapper">

  <div class="schedule-day">
    <div class="day-heading">Thursday, November 26, 2026</div>
    <table class="schedule-table">
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-break"><td class="time">09:30 – 10:00</td><td>Welcome / Coffee</td></tr>
        <tr class="row-plenary"><td class="time">10:00 – 10:45</td><td>Speaker 1</td></tr>
        <tr class="row-talk"><td class="time">10:45 – 11:15</td><td>Speaker 2</td></tr>
        <tr class="row-break"><td class="time">11:15 – 11:30</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">11:30 – 11:55</td><td>Speaker 3</td></tr>
        <tr class="row-talk"><td class="time">11:55 – 12:20</td><td>Speaker 4</td></tr>
        <tr class="row-break"><td class="time">12:20 – 13:50</td><td>Lunch break</td></tr>
        <tr class="row-plenary"><td class="time">13:50 – 14:35</td><td>Speaker 5</td></tr>
        <tr class="row-talk"><td class="time">14:35 – 15:00</td><td>Speaker 6</td></tr>
        <tr class="row-talk"><td class="time">15:00 – 15:25</td><td>Speaker 7</td></tr>
        <tr class="row-talk"><td class="time">15:25 – 15:50</td><td>Speaker 8</td></tr>
        <tr class="row-break"><td class="time">15:50 – 16:15</td><td>Coffee break</td></tr>
        <tr class="row-plenary"><td class="time">16:15 – 17:00</td><td>Speaker 9</td></tr>
        <tr class="row-talk"><td class="time">17:00 – 17:25</td><td>Speaker 10</td></tr>
        <tr class="row-break"><td class="time">17:25 – 18:00</td><td>Discussion</td></tr>
      </tbody>
    </table>
  </div>

  <div class="schedule-day">
    <div class="day-heading">Friday, November 27, 2026</div>
    <table class="schedule-table">
      <thead>
        <tr><th>Time</th><th>Event</th></tr>
      </thead>
      <tbody>
        <tr class="row-plenary"><td class="time">09:15 – 10:00</td><td>Speaker 1</td></tr>
        <tr class="row-talk"><td class="time">10:00 – 10:25</td><td>Speaker 2</td></tr>
        <tr class="row-break"><td class="time">10:25 – 10:50</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">10:50 – 11:15</td><td>Speaker 3</td></tr>
        <tr class="row-plenary"><td class="time">11:15 – 12:00</td><td>Speaker 4</td></tr>
        <tr class="row-break"><td class="time">12:00 – 13:40</td><td>Lunch break</td></tr>
        <tr class="row-plenary"><td class="time">13:40 – 14:25</td><td>Speaker 5</td></tr>
        <tr class="row-talk"><td class="time">14:25 – 14:50</td><td>Speaker 6</td></tr>
        <tr class="row-talk"><td class="time">14:50 – 15:15</td><td>Speaker 7</td></tr>
        <tr class="row-talk"><td class="time">15:15 – 15:40</td><td>Speaker 8</td></tr>
        <tr class="row-break"><td class="time">15:40</td><td>Discussion / Closing</td></tr>
      </tbody>
    </table>
  </div>

</div>