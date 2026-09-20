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

.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 30px;
}

.project-card {
  display: block;
  text-decoration: none !important;
  color: inherit !important;
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  overflow: hidden;
  background: #fff;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 18px rgba(0,0,0,0.1);
}

.project-card-image {
  width: 100%;
  height: 230px;
  object-fit: cover;
  display: block;
}

.project-card-content {
  padding: 20px;
}

.project-card-category {
  margin: 0 0 8px;
  color: #777 !important;
  font-size: 11px;
  line-height: 1.2;
  letter-spacing: 0.12em;
  font-weight: 600;
}

.project-card-title {
  margin: 0 0 10px;
  color: #111 !important;
  font-size: 22px;
  line-height: 1.3;
  font-weight: 600;
}

.project-card-strapline {
  margin: 0;
  color: #555 !important;
  font-size: 15px;
  line-height: 1.55;
  font-style: italic;
}

.dissertation-heading {
  font-size: 20px;
  line-height: 1.4;
  font-style: italic;
  color: #f2f2f2 !important;
  margin: 55px 0 10px;
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
  color: #fff !important;
  text-decoration: underline !important;
}

.dissertation-description {
  font-size: 15px;
  line-height: 1.5;
  color: #bdbdbd !important;
  margin: 0;
}

@media (max-width: 800px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }

  .project-card-image {
    height: auto;
    max-height: 320px;
  }
}
</style>


<p class="project-intro">
  Independent longform projects
</p>

<hr class="project-divider">


<div class="projects-grid">

  <!-- ANTS -->

  <a
    class="project-card"
    href="{{ '/ants/' | relative_url }}">

    <img
      class="project-card-image"
      src="{{ '/assets/img/ants.jpg' | relative_url }}"
      alt="Ants">

    <div class="project-card-content">

      <p class="project-card-category">
        SCIENCE
      </p>

      <p class="project-card-title">
        Ants: the 150 years old success story
      </p>

      <p class="project-card-strapline">
        Naturalists, experimentalists, and theoreticians have devoted themselves to these efficient little creatures.
      </p>

    </div>

  </a>


  <!-- NDM-1 -->

  <a
    class="project-card"
    href="{{ '/ndm-1/' | relative_url }}">

    <img
      class="project-card-image"
      src="{{ '/assets/img/medical-tourism.jpg' | relative_url }}"
      alt="NDM-1">

    <div class="project-card-content">

      <p class="project-card-category">
        HEALTH
      </p>

      <p class="project-card-title">
        NDM-1: A tourist and a threat
      </p>

      <p class="project-card-strapline">
        As NDM-1 began its voyage through the bacterial kingdom, it gave bacteria the power to resist a majority of antibiotics.
      </p>

    </div>

  </a>


  <!-- BEACHED TURTLES -->

  <a
    class="project-card"
    href="{{ '/beached-turtles/' | relative_url }}">

    <img
      class="project-card-image"
      src="{{ '/assets/img/beached-turtles.jpg' | relative_url }}"
      alt="Beached Olive Ridley turtles">

    <div class="project-card-content">

      <p class="project-card-category">
        ECOLOGY
      </p>

      <p class="project-card-title">
        Over 1,000 dead: Beached turtles demand collaborative effort
      </p>

      <p class="project-card-strapline">
        Ecologists say the turtle crisis points to a larger collapse of the marine ecosystem.
      </p>

    </div>

  </a>


  <!-- PATTA -->

  <a
    class="project-card"
    href="{{ '/patta/' | relative_url }}">

    <img
      class="project-card-image"
      src="{{ '/assets/img/patta.jpg' | relative_url }}"
      alt="Injambakkam, Chennai">

    <div class="project-card-content">

      <p class="project-card-category">
        INFRASTRUCTURE
      </p>

      <p class="project-card-title">
        The patta mystery behind Chennai’s rapid development
      </p>

      <p class="project-card-strapline">
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
