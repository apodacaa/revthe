<template>
  <div class="container">
    <div>
      <Logo />
      <div class="links">
        <a class="button is-outlined is-primary"
          target="_blank"
        >
          ABOUT
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.links {
  padding-top: 15px;
}
</style>