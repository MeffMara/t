<template>
  <div class="container">
    <div class="row position-relative">
      <div class="col-7">
        <h2 class="hero__header">{{ header }}</h2>
        <p> {{ description }} </p>
        <primary-button :label=buttonLabel />
      </div>
      <div class="col-5">
        <img src="/svg/hero.svg" alt="hero">
      </div>
      <div class="hero__scroll position-absolute">
        <span>scroll</span>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
import PrimaryButton from '../App/Buttons/PrimaryButton.vue'

  export default Vue.extend({
  components: { PrimaryButton },
    data() {
      return {
        header: 'Welcome to Zubi-Solutions !',
        description: 'Looking for Right job that you deserve? We are here to help you!',
        buttonLabel: 'Send a resume'
      }
    },
  })
</script>

<style scoped>

</style>
