<template>
  <div class="container">
    <div>
      <Logo />
      <div class="links">
        <NuxtLink
          class="button is-outlined is-primary"
          target="_blank"
          to="/about"
        >
          About
        </NuxtLink>
        <a class="button is-outlined is-primary" target="_blank">Contact</a>
        <a class="button is-outlined is-primary" target="_blank">COVID-19</a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
