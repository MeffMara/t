<template>
  <Tutorial />
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',

   async asyncData({ $content }:any) {
    const posts = await $content("blog").fetch();

    return {
      posts,
    };
  },
})
</script>
