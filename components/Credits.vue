<template>
  <section class="content" id="credits">
    <div class="image__wrapper">
      <img src="/images/wolf3x.jpg" alt="Portrait Luisa" class="image">
    </div>
    <div class="copy__wrapper">
      <p class="copy">
        mma film presents a fh salzburg production a film by daniela jud „luisa“ with katharina sporrer wolf danny homann laura hermann darko vladetic cinematographer georg sommer artdirection kerstin maria gatterbauer make up artist christina sieberer produced by mariia deikova editing imanuel thallinger music by karin pallier sounddesign by david maislinger
      </p>
    </div>
    <div class="logos">
      <a href="http://"><img src="/images/wolf.jpg" alt="Fh Salzburg Logo" class="logo"></a>
      <a href="http://"><img src="/images/wolf.jpg" alt="MMA Logo" class="logo"></a>
    </div>
  </section>
</template>

<style scoped>
.content {
  min-height: 100vh;
  position: relative;
  display: flex;
  flex-direction: column;
}

.image {
  width: 100%;
  height: auto;
  display: block;
}

.image__wrapper {
  flex: 3;
  width: 100%;
  overflow: hidden;
  max-height: 30em;
}

.copy__wrapper {
  flex: 2;
  text-align: center;
  background: #000000;
  color: #fff;
  display: flex;
  padding: 5rem 0;
}

.copy {
  width: 70%;
  margin: auto;
  text-transform: uppercase;
}

.logos {
  flex: 1;
  background: #222222;
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo {
  max-width: 120px;
  margin: 2rem .2rem;
}


@media (max-width: 30em) {
  .content {
    padding: 0;
    min-height: initial;
  }
}
</style>
