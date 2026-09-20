---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
---

<style>
.project-intro {
  font-size: 20px;
  line-height: 1.4;
  font-style: italic;
  color: #f2f2f2 !important;
  margin: 0 0 10px;
}

.project-divider {
  border: 0;
  border-top: 1px solid #d9d9d9;
  margin: 0 0 35px;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 30px;
  margin-top: 0;
  margin-bottom: 55px;
}

.project-card {
  display: block;
  border: 1px solid #dcdcdc;
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
  text-decoration: none !important;
  color: #222 !important;
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
  background: #fff;
}

.project-card-label {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #777 !important;
  margin: 0 0 9px;
  font-weight: 500;
}

.project-card-title {
  font-size: 19px;
  line-height: 1.3;
  font-weight: 600;
  color: #222 !important;
  margin: 0 0 9px;
}

.project-card-description {
  font-size: 15px;
  line-height: 1.5;
  color: #666 !important;
  margin: 0;
}

.dissertation-heading {
  font-size: 20px;
  line-height: 1.4;
  font-style: italic;
  color: #f2f2f2 !important;
  margin: 0 0 10px;
}

.dissertation-divider {
  border: 0;
  border-top: 1px solid #d9d9d9;
  margin: 0 0 35px;
}

.dissertation-section {
  max-width: 700px;
  margin-bottom: 55px;
}

.dissertation-label {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #bdbdbd !important;
  margin: 0 0 9px;
  font-weight: 500;
}

.dissertation-title {
  font-size: 22px;
  line-height: 1.3;
  font-weight: 600;
  margin: 0 0 10px;
}

.dissertation-title a {
  color: #f2f2f2 !important;
  text-decoration: none !important;
}

.dissertation-title a:hover {
  color: #ffffff !important;
  text-decoration: underline !important;
}

.dissertation-description {
  font-size: 15px;
  line-height: 1.5;
  color: #bdbdbd !important;
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


<p class="project-intro">
  Independent longform projects
</p>

<hr class="project-divider">


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
      <div class="project-card-label">SCIENCE</div>

      <div class="project-card-title">
        Ants: the 150 years old success story
      </div>

      <p class="project-card-description">
        Naturalists, experimentalists, and theoreticians have devoted themselves to these efficient little creatures.
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
      <div class="project-card-label">HEALTH</div>

      <div class="project-card-title">
        NDM-1: A tourist and a threat
      </div>

      <p class="project-card-description">
        As NDM-1 began its voyage through the bacterial kingdom, it gave bacteria the power to resist a majority of antibiotics.
      </p>
    </div>

  </a>


  <a class="project-card"
     href="#"
     target="_blank"
     rel="noopener">

    <img
      class="project-card-image"
      src="{{ '/assets/img/beached-turtles.jpg' | relative_url }}"
      alt="Beached turtles project">

    <div class="project-card-content">
      <div class="project-card-label">ECOLOGY</div>

      <div class="project-card-title">
        Over 1,000 dead: Beached turtles demand collaborative effort
      </div>

      <p class="project-card-description">
        Ecologists say the turtle crisis points to a larger collapse of the marine ecosystem.
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
      <div class="project-card-label">INFRASTRUCTURE</div>

      <div class="project-card-title">
        The patta mystery behind Chennai’s rapid development
      </div>

      <p class="project-card-description">
        Unproven claims aside, lavishness and relocation threats continue to coexist along either sides of the Buckingham Canal.
      </p>
    </div>

  </a>

</div>


<p class="dissertation-heading">
  Dissertation
</p>

<hr class="dissertation-divider">


<div class="dissertation-section">

  <div class="dissertation-label">
    DISSERTATION
  </div>

  <div class="dissertation-title">
    <a
      href="https://drive.google.com/file/d/1WZ2x1yN5hwP-pY58kxNhQhpgZz8eEnmB/view"
      target="_blank"
      rel="noopener">
      The Rise of Fungal Diseases
    </a>
  </div>

  <p class="dissertation-description">
    Academic dissertation · Asian College of Journalism
  </p>

</div>
