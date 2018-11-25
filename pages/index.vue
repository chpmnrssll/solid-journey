<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">solid-journey</h1>
      <h2 class="subtitle">A Nuxt.js Project</h2>
      <ul class="list">
        <li><a href="https://nuxtjs.org/">Nuxt.js</a></li>
        <li><a href="https://docs.docker.com/compose/">Docker Compose</a></li>
        <li><a href="https://www.docker.com/">Docker</a></li>
        <li><a href="https://docs.travis-ci.com/">Travis-CI</a></li>
        <li><a href="https://pages.github.com/">Github Pages</a></li>
        <li><a href="https://developers.google.com/search/docs/guides/">Structured Data</a></li>
        <li><a href="http://schema.org/">schema.org</a></li>
        <li><a href="https://json-ld.org/">json-ld.org</a></li>
        <li><a href="https://www.ampproject.org/learn/overview/">AMP</a></li>
      </ul>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.list {
  list-style: none;
}
</style>
