---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 30px;
  margin-top: 30px;
  margin-bottom: 55px;
}

.project-card {
  display: block;
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 18px rgba(0,0,0,0.08);
}

.project-card-image {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}

.project-card-content {
  padding: 20px 20px 24px;
}

.project-card-label {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #777;
  margin: 0 0 9px;
  font-weight: 500;
}

.project-card-title {
  font-size: 22px;
  line-height: 1.3;
  font-weight: 600;
  margin: 0;
}

.project-divider {
  border: 0;
  border-top: 1px solid #d9d9d9;
  margin: 50px 0 45px;
}

.dissertation-heading {
  margin-bottom: 25px;
}

.dissertation-card {
  display: block;
  max-width: 620px;
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  padding: 24px 24px 26px;
  background: #fff;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.dissertation-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 18px rgba(0,0,0,0.08);
}

.dissertation-title {
  font-size: 22px;
  line-height: 1.3;
  font-weight: 600;
  margin: 0 0 10px;
}

.dissertation-description {
  font-size: 15px;
  line-height: 1.5;
  color: #777;
  margin: 0;
}

@media (max-width: 700px) {
  .project-grid {
    grid-template-columns: 1fr;
  }

  .project-card-image {
    height: 210px;
  }
}
</style>


<p>
  Reporting, stories and projects developed independently.
</p>


<div class="project-grid">

  <a class="project-card"
     href="#"
     target="_blank"
     rel="noopener">

    <img
      class="project-card-image"
      src="{{ '/assets/img/ants.jpg' | relative_url }}"
      alt="Ants project">

    <div class="project-card-content">
      <p class="project-card-label">PROJECT</p>

      <p class="project-card-title">
        Ants
      </p>
    </div>

  </a>


  <a class="project-card"
     href="#"
     target="_blank"
     rel="noopener">

    <img
      class="project-card-image"
      src="{{ '/assets/img/medical-tourism.jpg' | relative_url }}"
      alt="Medical tourism project">

    <div class="project-card-content">
      <p class="project-card-label">PROJECT</p>

      <p class="project-card-title">
        Medical Tourism
      </p>
    </div>

  </a>


  <a class="project-card"
     href="#"
     target="_blank"
     rel="noopener">

    <img
      class="project-card-image"
      src="{{ '/assets/img/turtles.jpg' | relative_url }}"
      alt="Beached turtles project">

    <div class="project-card-content">
      <p class="project-card-label">PROJECT</p>

      <p class="project-card-title">
        Beached Turtles
      </p>
    </div>

  </a>


  <a class="project-card"
     href="#"
     target="_blank"
     rel="noopener">

    <img
      class="project-card-image"
      src="{{ '/assets/img/patta.jpg' | relative_url }}"
      alt="Patta project">

    <div class="project-card-content">
      <p class="project-card-label">PROJECT</p>

      <p class="project-card-title">
        Patta
      </p>
    </div>

  </a>

</div>


<hr class="project-divider">


## Dissertation

<a class="dissertation-card"
   href="https://drive.google.com/file/d/1WZ2x1yN5hwP-pY58kxNhQhpgZz8eEnmB/view"
   target="_blank"
   rel="noopener">

  <p class="project-card-label">DISSERTATION</p>

  <p class="dissertation-title">
    The Rise of Fungal Diseases
  </p>

  <p class="dissertation-description">
    Academic dissertation · Asian College of Journalism
  </p>

</a>
