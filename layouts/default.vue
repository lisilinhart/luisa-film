<template>
  <div>
    <nuxt/>
  </div>
</template>


<script>
import Navigation from '~/components/Navigation'

export default {
  components: {
    Navigation,
  }
}
</script>

<style>
@font-face {
  font-family: "Bauer Bodoni";
  src: url("~/fonts/Bauer-Bodoni.woff") format("woff"),
    url("~/fonts/Bauer-Bodoni.woff2") format("woff2");
  font-weight: normal;
  font-style: normal;
}

html, body {
  width: 100%;
  box-sizing: border-box;
  margin: 0;
}

html {
  font-family: "Georgia", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.link {
  color: inherit;
  text-decoration: none;
}

.title {
  font-family: "Bauer Bodoni", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 7rem;
  text-transform: uppercase;
  letter-spacing: 2rem;
}

.subtitle {
  font-family: "Bauer Bodoni", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  text-transform: uppercase;
  font-size: 2.2rem;
  letter-spacing: .5rem;
  text-align: right;
}

.copy {
  line-height: 1.5;
}

.mr {
  margin-right: .3rem;
}

.mr3 {
  margin-right: 2.5rem;
}

@media (max-width: 30em) {
  html {
    font-size: 12px;
  }

  .image {
    width: 100%;
    height: auto;
  }

  .subtitle {
    text-align: left;
    margin: 1em 0;
  }

  .content {
    display: block;
    min-height: initial;
    padding: 2em 1em;
  }
}
</style>
