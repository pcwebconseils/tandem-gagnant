<template>
  <main class="container-fluid">
    <section class="row justify-content-left">
      <div class="col-md-2 m-5">
        <logo />
      </div>
      <nuxt-link to="/" class="links">
      <article class="col-md-4 about">
        <h2>Titre</h2>
        <p>Présentation</p>
        <img src="@/static/logo.png" alt="a propos de tandem gangant">
      </article>
      </nuxt-link>
    </section>
  </main>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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

.links {
  padding-top: 15px;
  color: #35495e;
}
.links:hover{
  text-decoration: none;
  color: #35495e;
  font-size: 3em;
}
.about{
  overflow: hidden;
  max-width: 400px;
  min-width: 400px;
  width: 400px;
  height: 400px;
  border: 1px solid black;
  border-radius: 50%;
  text-align: center;
}
</style>
