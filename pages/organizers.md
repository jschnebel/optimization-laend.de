---
layout: page
title: Organizers
permalink: /organizers/
---

<style>
  .organizer {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
    margin-bottom: 3rem;
    padding-bottom: 3rem;
    border-bottom: 1px solid #e0e0e0;
  }

  .organizer:last-child {
    border-bottom: none;
  }

  .organizer-photo {
    width: 160px;
    min-width: 160px;
    height: 160px;
    border-radius: 50%;
    background-color: #dce8f7;
    overflow: hidden;
  }

  .organizer-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    border-radius: 50%;
  }

  .organizer-photo.zoom img {
    transform: scale(1.8);
    transform-origin: center;
  }

  .organizer-info h2 {
    margin-top: 0;
    color: #4a6fa5;
    font-size: 1.3rem;
    display: flex;
    align-items: center;
    gap: 0.6rem;
  }

  .email-icon {
    color: #4a6fa5;
    text-decoration: none;
    font-size: 1.8rem;
    opacity: 0.7;
    transition: opacity 0.2s;
  }

  .email-icon:hover {
    opacity: 1;
  }

  .organizer-info p {
    color: #444;
    line-height: 1.7;
    font-size: 0.95rem;
  }

  @media (max-width: 600px) {
    .organizer {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  }
</style>

<div class="organizer">
  <div class="organizer-photo zoom">
    <img src="{{ site.baseurl }}/assets/Staudigl.jpg" alt="Mathias Staudigl" />
  </div>
  <div class="organizer-info">
    <h2>Prof. Mathias Staudigl <a class="email-icon" href="mailto:m.staudigl@uni-mannheim.de" title="m.staudigl@uni-mannheim.de">✉</a></h2>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    </p>
    <p>
      Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
    </p>
  </div>
</div>

<div class="organizer">
  <div class="organizer-photo">
    <img src="{{ site.baseurl }}/assets/Herzog.jpg" alt="Roland Herzog" />
  </div>
  <div class="organizer-info">
    <h2>Prof. Roland Herzog <a class="email-icon" href="mailto:roland.herzog@iwr.uni-heidelberg.de" title="roland.herzog@iwr.uni-heidelberg.de">✉</a></h2>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    </p>
    <p>
      Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
    </p>
  </div>
</div>