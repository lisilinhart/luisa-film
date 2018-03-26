<template>
  <section class="content" id="synopsis">
    <div class="image__wrapper">
      <img src="/images/katharina2x.jpg" alt="Portrait Luisa" class="image">
    </div>
    <h1 class="subtitle">Synopsis</h1>
    <p class="copy">
      Wien 1929: Die junge lebensfrohe Prostituierte namens Luisa schafft einen unglaublichen
      finanziellen Aufstieg, indem sie Menschen, die nicht mehr leben wollen, tötet.
      Eines Tages kommen ihre Taten ans Licht und es prallen zwei Sichtweißen aufeinander.
      Luisa versucht ihren Mitmenschen den schmalen Grad zwischen Sterbehilfe und Mord
      aufzuzeigen, jedoch stößt sie auf wenig Verständnis und steht kurz davor als Mörderin zum
      Tode verurteilt zu werden.
    </p>
  </section>
</template>

<style scoped>
.content {
  padding: 2rem 3rem 2rem 0;
  display: grid;
  min-height: 100vh;

  display: grid;
  grid-template-areas:
  "img . ."
  "img h1 h1"
  "img copy .";
  grid-column-gap: 4.5rem;
  grid-row-gap: 1rem;
  grid-template-rows: .5fr 1fr 4fr;
  grid-template-columns: 3fr 2fr 1fr;
}

.subtitle {
  grid-area: h1;
}

.image {
  height: 100%;
  width: auto;
}

.image__wrapper {
  height: 100%;
  overflow: hidden;
  grid-area: img;
}

.copy {
  grid-area: copy;
}

@media (max-width: 50em) {
  .content {
    display: block;
    min-height: initial;
    padding: 2em 1em;
  }

  .image {
    width: 100%;
    height: auto;
  }

  .subtitle {
    text-align: left;
    margin: 1em 0;
  }
}
</style>
