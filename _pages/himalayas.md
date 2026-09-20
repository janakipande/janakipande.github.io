---
layout: page
title: Himalayas
permalink: /himalayas/
nav: true
nav_order: 4
---

<style>
.himalaya-feature-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px;
  margin-top: 28px;
  margin-bottom: 50px;
}

.himalaya-article-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 28px;
  margin-top: 28px;
  margin-bottom: 55px;
}

.himalaya-card {
  display: block;
  border: 1px solid #e5e7eb;
  border-radius: 10px;
  overflow: hidden;
  background: #fff;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.himalaya-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 18px rgba(0,0,0,0.08);
}

.himalaya-card-image {
  width: 100%;
  height: 190px;
  object-fit: cover;
  display: block;
}

.himalaya-placeholder {
  width: 100%;
  height: 190px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f3f4f6;
  color: #9ca3af;
  font-size: 40px;
}

.himalaya-card-content {
  padding: 18px 18px 22px;
}

.himalaya-card-label {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #777;
  margin: 0 0 9px;
  font-weight: 500;
}

.himalaya-card-title {
  font-size: 19px;
  line-height: 1.35;
  font-weight: 600;
  margin: 0;
  color: #444 !important;
}

.himalaya-intro {
  font-size: 16px;
  line-height: 1.6;
  margin-top: -10px;
  margin-bottom: 28px;
  color: #777;
}

.himalaya-divider {
  border: 0;
  border-top: 1px solid #d9d9d9;
  margin: 45px 0 50px;
}

@media (max-width: 900px) {
  .himalaya-article-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 650px) {
  .himalaya-feature-grid,
  .himalaya-article-grid {
    grid-template-columns: 1fr;
  }

  .himalaya-card-image,
  .himalaya-placeholder {
    height: 200px;
  }
}
</style>


<p class="himalaya-intro">
  <em>The Himalayas are where some of the most visible impacts of climate change, technological expansion and ecosystem collapse are unfolding.</em>
</p>

<div class="himalaya-feature-grid">

  <a class="himalaya-card"
     href="https://www.youtube.com/watch?v=6iCasx5np84"
     target="_blank"
     rel="noopener">

    <img
      class="himalaya-card-image"
      src="https://img.youtube.com/vi/6iCasx5np84/maxresdefault.jpg"
      alt="Himalayas documentary">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">DOCUMENTARY</p>

      <p class="himalaya-card-title">
        Impact of climate change on agriculture in Uttarakhand
      </p>
    </div>

  </a>


  <a class="himalaya-card"
     href="https://preview.shorthand.com/gxCpcWyATRo1lQ2z"
     target="_blank"
     rel="noopener">

    <img
      class="himalaya-card-image"
      src="{{ '/assets/img/shorthand.jpg' | relative_url }}"
      alt="Himalayas Shorthand story">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">SHORTHAND</p>

      <p class="himalaya-card-title">
        Road expansion in the Himalayas leaves fractures in a fragile ecosystem
      </p>
    </div>

  </a>

</div>


<hr class="himalaya-divider">


## Features & Profiles

<div class="himalaya-article-grid">

  <a class="himalaya-card"
     href="https://theprint.in/environment/young-rising-himalayas-prone-disasters/3026893/"
     target="_blank"
     rel="noopener">

    <img
      class="himalaya-card-image"
      src="{{ '/assets/img/mountain.jpg' | relative_url }}"
      alt="Himalayas">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">CLIMATE</p>

      <p class="himalaya-card-title">
        Why the young, rising Himalayas are so prone to disasters
      </p>
    </div>

  </a>


  <a class="himalaya-card"
     href="https://theprint.in/feature/nepals-climate-compensation-call-tests-un-loss-and-damage-fund/3034305/"
     target="_blank"
     rel="noopener">

    <img
      class="himalaya-card-image"
      src="https://staticprintenglish.theprint.in/wp-content/uploads/2026/08/Raul-John-Aju-1-1-e1788251866222-696x392.jpg"
      alt="Nepal flash floods">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">CLIMATE</p>

      <p class="himalaya-card-title">
        Nepal’s climate compensation call tests UN Loss and Damage Fund
      </p>
    </div>

  </a>


  <a class="himalaya-card"
     href="https://theprint.in/science/mosquitoes-malaria-himachal-pradesh-kangra-himalayas/2940934/"
     target="_blank"
     rel="noopener">

    <img
      class="himalaya-card-image"
      src="{{ '/assets/img/mosquito.jpg' | relative_url }}"
      alt="Mosquito">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">CLIMATE</p>

      <p class="himalaya-card-title">
        Why mosquitoes have invaded cold Himalayan foothills
      </p>
    </div>

  </a>


  <a class="himalaya-card"
   href="{{ '/koti/' | relative_url }}">

  <img
    class="himalaya-card-image"
    src="{{ '/assets/img/koti.jpg' | relative_url }}"
    alt="Koti Profile">

  <div class="himalaya-card-content">
    <p class="himalaya-card-label">PROFILE</p>

    <p class="himalaya-card-title">
      The struggles of a farmer in Uttarakhand
    </p>
  </div>

</a>


  <div class="himalaya-card">

    <img
      class="himalaya-card-image"
      src="{{ '/assets/img/dalit.jpg' | relative_url }}"
      alt="Dalit Article">

    <div class="himalaya-card-content">
      <p class="himalaya-card-label">CLIMATE</p>

      <p class="himalaya-card-title">
        Uttarakhand remains divided by the invisible wall of caste
      </p>
    </div>

  </div>

</div>
