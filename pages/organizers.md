---
layout: page
title: Organizers
permalink: /organizers/
---

<style>
  .organizers-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
  }

  .organizer-card {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 1rem;
    border-radius: 8px;
    background: #f9f9f9;
    transition: background 0.2s;
  }

  .organizer-card:hover {
    background: #f0f5ff;
  }

  .organizer-photo {
    width: 80px;
    min-width: 80px;
    height: 80px;
    border-radius: 50%;
    overflow: hidden;
    background-color: #dce8f7;
  }

  .organizer-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .organizer-photo.zoom img {
    transform: scale(1.6);
    transform-origin: center;
  }

  .organizer-info {
    flex: 1;
  }

  .organizer-info h3 {
    margin: 0 0 0.3rem 0;
    color: #4a6fa5;
    font-size: 1.05rem;
    font-weight: 600;
  }

  .organizer-info a {
    color: #666;
    text-decoration: none;
    font-size: 0.88rem;
    transition: color 0.2s;
  }

  .organizer-info a:hover {
    color: #4a6fa5;
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .organizers-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="organizers-grid">

  <div class="organizer-card">
    <div class="organizer-photo zoom">
      <img src="{{ site.baseurl }}/assets/Staudigl.jpg" alt="Mathias Staudigl" />
    </div>
    <div class="organizer-info">
      <h3>Prof. Dr. Mathias Staudigl</h3>
      <a href="mailto:m.staudigl@uni-mannheim.de">Mail</a>
    </div>
  </div>

  <div class="organizer-card">
    <div class="organizer-photo">
      <img src="{{ site.baseurl }}/assets/Herzog.jpg" alt="Roland Herzog" />
    </div>
    <div class="organizer-info">
      <h3>Prof. Dr. Roland Herzog</h3>
      <a href="mailto:roland.herzog@iwr.uni-heidelberg.de">Mail</a>
    </div>
  </div>

  <div class="organizer-card">
    <div class="organizer-photo">
      <img src="{{ site.baseurl }}/assets/Andrea.jpg" alt="Andrea" />
    </div>
    <div class="organizer-info">
      <h3>Dr. Andrea Ebner</h3>
      <a href="andrea.ebner@uni-mannheim.de">Mail</a>
    </div>
  </div>

  <div class="organizer-card">
    <div class="organizer-photo">
      <img src="{{ site.baseurl }}/assets/Meggie.png" alt="Meggie" />
    </div>
    <div class="organizer-info">
      <h3>Meggie Marschner</h3>
      <a href="mailto:meggie.marschner@uni-mannheim.de">Mail</a>
    </div>
  </div>

  <div class="organizer-card">
    <div class="organizer-photo">
      <img src="{{ site.baseurl }}/assets/Siqi.jpeg" alt="Siqi" />
    </div>
    <div class="organizer-info">
      <h3>Siqi Qu</h3>
      <a href="mailto:siqi.qu@uni-mannheim.de">Mail</a>
    </div>
  </div>

  <div class="organizer-card">
    <div class="organizer-photo">
      <img src="{{ site.baseurl }}/assets/Johannes.jpg" alt="Johannes" />
    </div>
    <div class="organizer-info">
      <h3>Johannes Schnebel</h3>
      <a href="mailto:johannes-carl.schnebel@uni-mannheim.de">Mail</a>
    </div>
  </div>

</div>