---
layout: page
title: Video
permalink: /video/
nav: true
nav_order: 6
---

<style>
.video-intro {
  font-size: 18px;
  line-height: 1.6;
  font-style: italic;
  color: #f2f2f2 !important;
  font-weight: 500;
  margin: 0 0 25px;
}

.video-divider {
  border: 0;
  border-top: 1px solid #d9d9d9;
  margin: 0 0 32px;
}

.video-list {
  display: flex;
  flex-direction: column;
  gap: 14px;
}

.video-card {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 169px;
  gap: 20px;
  align-items: center;
  padding: 12px 14px;
  border: 1px solid #e5e7eb;
  border-radius: 8px;
  background: #fff;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.video-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
}

.video-card-content {
  min-width: 0;
}

.video-card-type {
  margin: 0 0 5px;
  color: #555 !important;
  font-size: 11px;
  line-height: 1.2;
  letter-spacing: 0.12em;
  font-weight: 600;
}

.video-card-title {
  margin: 0 0 8px;
  color: #000 !important;
  font-size: 19px;
  line-height: 1.35;
  font-weight: 600;
}

.video-card-description {
  margin: 0;
  color: #333 !important;
  font-size: 15px;
  line-height: 1.5;
}

.video-card-image {
  width: 169px;
  height: 95px;
  object-fit: contain;
  display: block;
  border-radius: 5px;
}

@media (max-width: 650px) {
  .video-card {
    grid-template-columns: 1fr;
  }

  .video-card-image {
    width: 100%;
    height: auto;
    max-height: 220px;
    object-fit: contain;
  }
}
</style>

<p class="video-intro">
  Interviews and on-camera explainers produced at <em>ThePrint</em>.
</p>

<hr class="video-divider">

<div class="video-list">

  <a class="video-card"
     href="https://www.youtube.com/watch?v=Iy_HxvwfDOM"
     target="_blank"
     rel="noopener">

    <div class="video-card-content">

      <p class="video-card-type">
        INTERVIEW
      </p>

      <p class="video-card-title">
        Sandesh Kadur's love letter to the Nilgiris
      </p>

      <p class="video-card-description">
        An interview with wildlife filmmaker and conservationist Sandesh Kadur.
      </p>

    </div>

    <img
      class="video-card-image"
      src="https://img.youtube.com/vi/Iy_HxvwfDOM/hqdefault.jpg"
      alt="Interview with Sandesh Kadur">

  </a>


  <a class="video-card"
     href="https://www.youtube.com/watch?v=1rYDqxuG0xM"
     target="_blank"
     rel="noopener">

    <div class="video-card-content">

      <p class="video-card-type">
        INTERVIEW
      </p>

      <p class="video-card-title">
        Can Pravaha University change Bihar?
      </p>

      <p class="video-card-description">
        An interview with Dr Pramath Raj Sinha and Dr Ajay Kumar, the founders of Pravaha University.
      </p>

    </div>

    <img
      class="video-card-image"
      src="https://img.youtube.com/vi/1rYDqxuG0xM/hqdefault.jpg"
      alt="Interview with Pravaha founders">

  </a>


  <a class="video-card"
     href="https://www.youtube.com/watch?v=HUJoyQ5Qlo4"
     target="_blank"
     rel="noopener">

    <div class="video-card-content">

      <p class="video-card-type">
        PROFILE
      </p>

      <p class="video-card-title">
        V Kamakoti: An academic full of contradictions
      </p>

      <p class="video-card-description">
        A video profile of IIT Madras director V. Kamakoti.
      </p>

    </div>

    <img
      class="video-card-image"
      src="https://img.youtube.com/vi/HUJoyQ5Qlo4/hqdefault.jpg"
      alt="Video profile of V. Kamakoti">

  </a>


  <a class="video-card"
     href="https://www.youtube.com/watch?v=P7Uog9IXiCw"
     target="_blank"
     rel="noopener">

    <div class="video-card-content">

      <p class="video-card-type">
        PROFILE
      </p>

      <p class="video-card-title">
        Rohan P Naidu: The quizzer who found a black hole star
      </p>

      <p class="video-card-description">
        A video profile of astrophysicist Rohan P Naidu.
      </p>

    </div>

    <img
      class="video-card-image"
      src="https://img.youtube.com/vi/P7Uog9IXiCw/hqdefault.jpg"
      alt="Video profile of Rohan P Naidu">

  </a>

</div>
