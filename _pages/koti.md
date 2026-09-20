---
layout: page
title: Koti article
permalink: /koti/
nav: false
---

<style>
.page-title {
  display: none !important;
}

.koti-page {
  max-width: 1100px;
  margin: 0 auto;
}

.koti-kicker {
  margin: 0 0 12px;
  font-size: 16px;
  color: #666;
}

.koti-headline {
  max-width: 760px;
  margin: 0 0 12px;
  font-size: 42px;
  line-height: 1.12;
  font-weight: 700;
}

/* First section: text on left, image on right */
.koti-section-one {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 48%;
  gap: 42px;
  align-items: start;
  margin-top: 20px;
}

.koti-section-one-text {
  max-width: 650px;
}

.koti-section-one-image img {
  width: 100%;
  height: auto;
  display: block;
}

/* Second section: image on left, text on right */
.koti-section-two {
  display: grid;
  grid-template-columns: 48% minmax(0, 1fr);
  gap: 42px;
  align-items: start;
  margin-top: 45px;
}

.koti-section-two-image img {
  width: 100%;
  height: auto;
  display: block;
}

.koti-section-two-text {
  max-width: 650px;
}

/* Final section */
.koti-final {
  max-width: 760px;
  margin: 45px auto 0;
}

.koti-page p {
  font-size: 17px;
  line-height: 1.75;
  margin: 0 0 22px;
}

/* Keep the opening and closing text comfortably readable */
.koti-section-one-text p,
.koti-section-two-text p,
.koti-final p {
  width: 100%;
}

@media (max-width: 800px) {

  .koti-headline {
    font-size: 34px;
  }

  .koti-section-one,
  .koti-section-two {
    display: block;
  }

  .koti-section-one-image,
  .koti-section-two-image {
    margin-bottom: 30px;
  }

  .koti-section-one-text,
  .koti-section-two-text,
  .koti-final {
    max-width: 760px;
  }
}
</style>

<div class="koti-page">

  <p class="koti-kicker">Uttarakhand, Koti</p>

  <h1 class="koti-headline">
    Challenges of farming amid climate change and migration
  </h1>


  <!-- FIRST SECTION -->

  <div class="koti-section-one">

    <div class="koti-section-one-text">

      <p>
        Bimla Devi has been farming in Koti, a small village in Uttarakhand,
        for decades. But farming is becoming increasingly difficult as the
        climate changes and younger members of the community leave the village
        in search of work.
      </p>

      <p>
        The changes are visible in the fields. Rainfall patterns have become
        less predictable, while water availability and crop yields have become
        harder to manage.
      </p>

      <p>
        For farmers like Devi, agriculture remains closely tied to everyday
        life. But the work is becoming more uncertain, particularly as
        traditional ways of farming have to contend with a changing climate.
      </p>

    </div>

    <div class="koti-section-one-image">

      <img
        src="{{ '/assets/img/koti.jpg' | relative_url }}"
        alt="Farming in Koti, Uttarakhand">

    </div>

  </div>


  <!-- SECOND SECTION -->

  <div class="koti-section-two">

    <div class="koti-section-two-image">

      <img
        src="{{ '/assets/img/koti2.jpg' | relative_url }}"
        alt="Landscape and farming in Koti, Uttarakhand">

    </div>

    <div class="koti-section-two-text">

      <p>
        Migration has added another layer to these challenges. As younger
        people leave the village for education and employment, fewer people
        remain to work on farms.
      </p>

      <p>
        This has left older residents carrying much of the responsibility for
        agricultural work. The loss of labour also makes it harder to maintain
        fields and continue farming practices that have been passed down
        through generations.
      </p>

      <p>
        Despite these difficulties, farming continues to be an important part
        of life in Koti. For residents who remain, the land provides both a
        livelihood and a connection to the place they call home.
      </p>

    </div>

  </div>


  <!-- FINAL SECTION -->

  <div class="koti-final">

    <p>
      The experience of farmers in Koti reflects a wider challenge facing
      Himalayan communities: adapting to a changing climate while dealing
      with the social and economic pressures that are reshaping rural life.
    </p>

    <p>
      For farmers like Bimla Devi, the future of agriculture will depend not
      only on the changing weather, but also on whether younger generations
      continue to see farming as a viable way of life.
    </p>

  </div>

</div>
