---
layout: page
permalink: /videos/
title: Videos
nav: true
nav_order: 3
---

<style>
.video-section-subtitle {
  font-size: 16px;
  line-height: 1.5;
  color: #555;
  margin: 0 0 24px;
  padding-bottom: 12px;
  border-bottom: 1px solid #d9d9d9;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  margin-top: 20px;
  margin-bottom: 60px;
}

.video-card {
  overflow: hidden;
  border: 1px solid #e5e7eb;
  border-radius: 9px;
  background: #fff;
}

.video-card-thumbnail {
  position: relative;
  display: block;
  width: 100%;
  height: 165px;
  overflow: hidden;
  background: #000;
}

.video-card-thumbnail img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.25s ease, opacity 0.25s ease;
}

.video-card:hover .video-card-thumbnail img {
  transform: scale(1.03);
  opacity: 0.9;
}

.video-card-content {
  padding: 13px 15px 15px;
}

.video-card-category {
  margin-bottom: 5px;
  font-size: 9px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #777;
}

.video-card h3 {
  margin: 0 0 7px;
  font-size: 16px;
  line-height: 1.4;
  color: #000 !important;
}

.video-card-description {
  margin: 0 0 10px;
  font-size: 12px;
  line-height: 1.5;
  color: #666;
}

.video-card a.watch-link {
  font-size: 12px;
  font-weight: 600;
  text-decoration: none;
}

@media (max-width: 1000px) {
  .video-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 600px) {
  .video-grid {
    grid-template-columns: 1fr;
    gap: 14px;
    margin-bottom: 45px;
  }
}
</style>

<p class="video-section-subtitle">Interviews, ground reports, and explainers produced at ThePrint.</p>

<div class="video-grid">

  <!-- NEW GROUND REPORT VIDEO 1 -->
  <div class="video-card">
    <a class="video-card-thumbnail" href="https://www.youtube.com/watch?v=7XAlBSOIV2w" target="_blank">
      <img src="https://img.youtube.com/vi/7XAlBSOIV2w/hqdefault.jpg" alt="How Uttar Pradesh's Shahjahanpur brought down stubble-burning fires">
    </a>
    <div class="video-card-content">
      <div class="video-card-category">Ground Report</div>
      <h3>How Uttar Pradesh's Shahjahanpur brought down stubble-burning fires</h3>
      <p class="video-card-description">
        How baler operators, compressed biogas plants, and late-night farmer chaupals curbed stubble burning in Shahjahanpur.
      </p>
      <a class="watch-link" href="https://www.youtube.com/watch?v=7XAlBSOIV2w" target="_blank">Watch video →</a>
    </div>
  </div>

  <!-- NEW GROUND REPORT VIDEO 2 -->
  <div class="video-card">
    <a class="video-card-thumbnail" href="https://www.youtube.com/watch?v=frRF9esLF-Y" target="_blank">
      <img src="https://img.youtube.com/vi/frRF9esLF-Y/hqdefault.jpg" alt="Two bustards, one shrinking desert: The race to save Rajasthan's Great Indian Bustard">
    </a>
    <div
