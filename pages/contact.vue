<template>
  <div class="container">
    <h1 class="title is-1">Contact</h1>
    <p><span class="text has-text-primary"><a href="mailto:contact@revelrytheater.com">Email</a></span></p>
    <p><a target="_blank" href="https://www.facebook.com/revelrytheater">Facebook</a></p>
    <p><a target="_blank" href="https://www.instagram.com/revelrytheater">Instagram</a></p>
    <p><a target="_blank" href="https://www.youtube.com/c/RevelryTheater">YouTube</a></p>
    <p><a target="_blank" href="https://twitter.com/revelrytheater">Twitter</a></p>
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
    //const slug = params.slug || "about";
    //const page = await $content(slug)
      //.fetch()
      //.catch(err => {
        //error({ statusCode: 404, message: "Page not found" });
      //});

    //return {
      //page
    //};
  //}
})
</script>