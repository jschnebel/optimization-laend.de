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
        <tr class="row-plenary"><td class="time">13:00 – 13:45</td><td>Long Talk</td></tr>
        <tr class="row-talk"><td class="time">13:45 – 14:05</td><td>Short Talk</td></tr>
        <tr class="row-talk"><td class="time">14:05 – 14:30</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">14:30 – 15:00</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">15:00 – 15:20</td><td>Short Talk</td></tr>
        <tr class="row-plenary"><td class="time">15:20 – 16:05</td><td>Long Talk</td></tr>
        <tr class="row-plenary"><td class="time">16:05 – 16:50</td><td>Long Talk</td></tr>
        <tr class="row-break"><td class="time">16:50 – 17:10</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">17:10 – 17:55</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">17:55 – 18:30</td><td>Discussion / Closing</td></tr>
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
        <tr class="row-plenary"><td class="time">09:00 – 09:45</td><td>Long Talk</td></tr>
        <tr class="row-talk"><td class="time">09:45 – 10:15</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">10:15 – 10:40</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">10:40 – 11:05</td><td>Short Talk</td></tr>
        <tr class="row-talk"><td class="time">11:05 – 11:30</td><td>Short Talk</td></tr>
        <tr class="row-talk"><td class="time">11:30 – 12:15</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">12:15 – 13:30</td><td>Lunch break</td></tr>
        <tr class="row-plenary"><td class="time">13:30 – 14:15</td><td>Long Talk</td></tr>
        <tr class="row-talk"><td class="time">14:15 – 14:40</td><td>Short Talk</td></tr>
        <tr class="row-talk"><td class="time">14:40 – 15:05</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">15:05 – 15:30</td><td>Coffee break</td></tr>
        <tr class="row-plenary"><td class="time">15:30 – 16:15</td><td>Long Talk</td></tr>
        <tr class="row-talk"><td class="time">16:15 – 16:30</td><td>Short Talk</td></tr>
        <tr class="row-plenary"><td class="time">16:30 – 17:15</td><td>Long Talk</td></tr>
        <tr class="row-break"><td class="time">17:25 – 18:00</td><td>Discussion / Closing</td></tr>
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
        <tr class="row-plenary"><td class="time">09:15 – 10:00</td><td>Long Talk</td></tr>
        <tr class="row-talk"><td class="time">10:00 – 10:25</td><td>Short Talk</td></tr>
        <tr class="row-break"><td class="time">10:25 – 10:50</td><td>Coffee break</td></tr>
        <tr class="row-talk"><td class="time">10:50 – 11:15</td><td>Short Talk</td></tr>
        <tr class="row-plenary"><td class="time">11:15 – 12:00</td><td>Long Talk</td></tr>
        <tr class="row-break"><td class="time">12:00 – 13:30</td><td>Lunch break</td></tr>
        <tr class="row-talk"><td class="time">13:30 – 13:55</td><td>Short Talk</td></tr>
        <tr class="row-talk"><td class="time">13:55 – 14:40</td><td>Long Talk</td></tr>
        <tr class="row-plenary"><td class="time">14:40 – 15:15</td><td>Long Talk</td></tr>
        <tr class="row-break"><td class="time">15:15</td><td>Discussion / Closing</td></tr>
      </tbody>
    </table>
  </div>

</div>