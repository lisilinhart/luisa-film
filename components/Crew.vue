<template>
  <section class="content" id="crew">
    <h1 class="subtitle">Crew</h1>
    <div class="slider">
      <div class="slider__tile mr">
        <img src="/images/mariiadeikova.jpg" alt="Maria Deikova" class="slider__image">
        <h3 class="slider__title">Maria Deikova</h3>
        <p class="slider__name">Production</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/danielajud.jpg" alt="Daniela Jud" class="slider__image">
        <h3 class="slider__title">Daniela Jud</h3>
        <p class="slider__name">Writer & Director</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/georgsommer.jpg" alt="Georg Sommer" class="slider__image">
        <h3 class="slider__title">Georg Sommer</h3>
        <p class="slider__name">Cinematographer</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/kerstinmariagatterbauer.jpg" alt="Kerstin Maria" class="slider__image">
        <h3 class="slider__title">Kerstin Maria</h3>
        <p class="slider__name">Art Direction</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/benkoeltringer.jpg" alt="Ben Költringer" class="slider__image">
        <h3 class="slider__title">Ben Költringer</h3>
        <p class="slider__name">Gaffer</p>
      </div>
      <div class="slider__tile">
        <img src="/images/christinasieberer.jpg" alt="Christina Sieberer" class="slider__image">
        <h3 class="slider__title">Christina Sieberer</h3>
        <p class="slider__name">Make up Artist</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.content {
  padding: 7rem 0 2rem 3rem;
  min-height: 100vh;
}

.subtitle {
  margin-right: 3rem;
  margin-bottom: 5rem;
}

.slider {
  width: 100%;
  overflow-x: scroll;
  display: flex;
}

.slider__tile {
  min-width: 10em;
}

.slider__title {
  font-weight: 600;
  line-height: 1.4;
  margin-bottom: .5em;
  font-size: 1em;
}

.slider__name {
  font-style: italic;
  font-size: .9em;
}

.slider__image {
  width: 100%;
  height: auto;
}

@media (max-width: 30em) {
  .content {
    padding: 2em 1em;
    min-height: initial;
  }

  .slider {
    flex-wrap: wrap;
  }

  .slider__tile {
    width: 45%;
    margin-bottom: 1em;
  }
}
</style>
