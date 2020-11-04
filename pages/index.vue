<template>
  <div class="container">
    <div>
      <Logo />
      <div class="links">
        <NuxtLink
          class="button is-outlined is-primary"
          to="/about"
        >
          About
        </NuxtLink>
        <NuxtLink
          class="button is-outlined is-primary"
          to="/people"
        >
          People
        </NuxtLink>
         <NuxtLink
          class="button is-outlined is-primary"
          to="/contact"
        >
          Contact
        </NuxtLink>
        <NuxtLink
          class="button is-outlined is-primary"
          to="/covid"
        >
          COVID-19
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>
