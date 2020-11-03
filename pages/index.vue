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
        <a class="button is-outlined is-primary">COVID-19</a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
