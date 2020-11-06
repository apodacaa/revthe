<template>
  <div class="container">
    <h1 class="title is-1">About</h1>
    <h2 class="title is-2">Mission</h2>
    <p>Revelry Theater is a small performing arts studio primarily used for classes and training in the areas of acting, improvisation, comedy, directing, and production. We also offer weekend showcases to foster the growth and education of our students and community.</p>
    <p>The main purpose of Revelry Theater is to assist individuals in becoming powerful and fearless performers, producers, and directors. We strive to remove any economic barriers to participation by keeping our classes, workshops, rentals, and shows as affordable as possible.</p>
    <p>Revelry Theater Inc is a non-profit 501(c)(3) corporation. Our board and staff is 100% volunteer.</p>
    <div class="links">
        <NuxtLink
          class="button is-outlined is-primary"
          to="/"
        >
          Revelry Theater
        </NuxtLink>
    </div>
  </div>
</template>

<script>
import Vue from 'vue'
export default Vue.extend({
  // async asyncData({ $content, params, error }) {
    // const slug = params.slug || "about";
    // const page = await $content(slug)
      // .fetch()
      // .catch(err => {
        // error({ statusCode: 404, message: "Page not found" });
      // });

    // return {
      // page
    // };
  // }
})
</script>


