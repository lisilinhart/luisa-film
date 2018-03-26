<template>
  <nav class="nav">
    <ul class="nav__list">
      <li class="nav__item mr3"><a href="#start" class="nav__link">Start</a></li>
      <li class="nav__item mr3"><a href="#synopsis" class="nav__link">Synopsis</a></li>
      <li class="nav__item mr3"><a href="#cast" class="nav__link">Cast</a></li>
      <li class="nav__item mr3"><a href="#crew" class="nav__link">Crew</a></li>
      <li class="nav__item"><a href="#credits" class="nav__link">Credits</a></li>
    </ul>
  </nav>
</template>

<script>
if(typeof window !== 'undefined') {
  window.addEventListener("scroll", () => {
    const menu = document.querySelector('.nav');

    if(document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) {
      menu.classList.add('visible');
    } else {
      menu.classList.remove('visible');
    }
  });
}
</script>

<style scoped>
.nav {
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: 2;
  font-family: "Bauer Bodoni", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  text-transform: uppercase;
  background: rgba(255,255,255, 0.4);
  padding: .3em 1em;
  opacity: 0;
  visibility: hidden;
  transition: opacity .5s ease-in-out, visibility .5s ease-in-out,;
}

.visible {
  opacity: 1;
  visibility: visible;
}

.nav__list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.nav__item {
  display: inline-block;
}

.nav__link {
  color: #000;
  text-decoration: none;
  letter-spacing: .1em;
  line-height: 1;
}

@media (max-width: 30em) {
  .nav {
    width: 100%;
    text-align: center;
  }
}

</style>
