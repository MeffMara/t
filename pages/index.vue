<template>
  <main>
    <Hero />
    <Vacancies />
    <WeOffer />
  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import Hero from '@/components/Hero/index.vue'
import Vacancies from '@/components/Vacancies/index.vue'
import WeOffer from '@/components/WeOffer/index.vue'


export default Vue.extend({
  name: 'IndexPage',
  components: {
    Hero,
    Vacancies,
    WeOffer
  },
  layout: 'default',

   async asyncData({ $content }:any) {
    const posts = await $content("blog").fetch();
    const pages = await $content("home").fetch();
    return {
      posts,
      pages,

    };

  },
})
</script>
