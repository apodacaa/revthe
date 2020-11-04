<template>
  <div class="container">
    <h1 class="title is-1">Covid-19</h1>
    <p>Well, shit.</p>
    <p>Despite our best efforts, there was simply no way to keep our doors open for the duration of this pandemic. We are not shutting down our business, but having our own space is off the table for the foreseeable future.</p>
    <p>We hope to open again once as conditions permit.</p>
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


