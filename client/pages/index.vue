<template>
  <section class="container">
    <h1 is="sui-header">nuxt-semantic-template</h1>
    <app-logo />
    <sui-message info>
      This project is a template in which scss and semantic ui are installed in nuxt.js
    </sui-message>
    <div>
      <sui-button primary>Primary</sui-button>
      <sui-button secondary>Secondary</sui-button>
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

<style lang="scss">
.container {
  text-align: center;
  min-height: 100vh;
  padding: 40px;
}
</style>

