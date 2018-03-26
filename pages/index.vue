<template>
  <article class="container" id="start">
    <section class="hero">
      <h1 class="title">
        Luisa
      </h1>
      <a href="http://www.facebook.com/luisaderfilm" class="link" target="__blank">facebook.com/luisaderfilm</a>
    </section>
    <navigation/>
    <synopsis/>
    <cast/>
    <crew/>
    <credits/>
  </article>
</template>

<script>
import Synopsis from '~/components/Synopsis'
import Cast from '~/components/Cast'
import Crew from '~/components/Crew'
import Credits from '~/components/Credits'
import Navigation from '~/components/Navigation'

export default {
  components: {
    Synopsis,
    Cast,
    Crew,
    Credits,
    Navigation
  }
}
</script>

<style>
.container {
  width: 100%;
}

.hero {
  width: 100%;
  min-height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: #222222;
  color: #ffffff;
  display: flex;
}

.link {
  position: absolute;
  bottom: 20px;
  right: 20px;
}
</style>
