<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        <!-- この下を Ulab Introductionに変更 -->
        Ulab git practice
      </h1>
      <h2 class="subtitle">
        <!-- この下を Ulab git practice by Nuxt.jsに変更 -->
        by Nuxt.js
      </h2>
      <div class="links">
        <nuxt-link
          to="/about"
          class="button--grey"
        >
          About
        </nuxt-link>
        <nuxt-link
          to="/design"
          class="button--green"
        >
          Design
        </nuxt-link>
        <nuxt-link
          to="/programming"
          class="button--lgreen"
        >
        Programming
        </nuxt-link>
        <nuxt-link
          to="/cad"
          class="button--brown"
        >
        CAD
        </nuxt-link>
      </div>
    </div>
  </div>
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
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  animation: 0.3s appear;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 80px;
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
}
</style>
