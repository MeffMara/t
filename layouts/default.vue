<template>
  <div>
    <AppHeader />
    <Nuxt />
    <AppFooter />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import AppHeader from '@/components/App/Header/index.vue'
import AppFooter from '@/components/App/Footer/index.vue'

export default Vue.extend({
  components: {
    AppHeader,
    AppFooter
  }
})
</script>
