<template>
  <section class="content" id="cast">
    <h1 class="subtitle">Cast</h1>
    <div class="slider">
      <div class="slider__tile mr">
        <img src="/images/katharina.jpg" alt="" class="slider__image">
        <h3 class="slider__title">Katharina Sporrer</h3>
        <p class="slider__name">Luisa</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/wolf.jpg" alt="" class="slider__image">
        <h3 class="slider__title">Wolf Danny Homann</h3>
        <p class="slider__name">Henri</p>
      </div>
      <div class="slider__tile mr">
        <img src="/images/laura.jpg" alt="" class="slider__image">
        <h3 class="slider__title">Laura Hermann</h3>
        <p class="slider__name">Ruth</p>
      </div>
      <div class="slider__tile">
        <img src="/images/wolf.jpg" alt="" class="slider__image">
        <h3 class="slider__title">Darko Vladetic</h3>
        <p class="slider__name">Nikola</p>
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
  display: flex;
  overflow-y: scroll;
}

.slider__tile {
  min-width: 10em;
  width: 25%;
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
