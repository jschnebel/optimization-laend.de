---
layout: page
title: Guest Registration
permalink: /registration/
---

<!--
  SETUP: replace GOOGLE_FORM_ID below with the ID of your Google Form.
  Google Form -> Send -> "<>" (embed) tab -> copy the src URL, which looks like
  https://docs.google.com/forms/d/e/XXXXXXXX/viewform?embedded=true
  Responses are stored in the linked Google Sheet only - never in this repository.
-->

<style>
  .registration-note {
    padding: 1rem 1.2rem;
    border-left: 4px solid #4fb1ba;
    background: rgba(79, 177, 186, 0.08);
    border-radius: 4px;
    margin-bottom: 1.5rem;
  }

  .registration-form {
    width: 100%;
    min-height: 1400px;
    border: 0;
  }
</style>

<div class="registration-note">
  <strong>This form is for guest attendees only.</strong><br>
  Invited speakers are already registered and do not need to fill it in.
</div>

<iframe class="registration-form"
        src="https://docs.google.com/forms/d/e/GOOGLE_FORM_ID/viewform?embedded=true"
        loading="lazy">
  Loading…
</iframe>

If the form does not load, you can
[open it in a new tab](https://docs.google.com/forms/d/e/GOOGLE_FORM_ID/viewform).
