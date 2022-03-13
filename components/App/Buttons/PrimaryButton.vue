<template>
  <div>
    <a :href='path'>{{ label }}
      <img src="/svg/big-arrow.svg" alt="arrow">
    </a>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    props: {
      label: {
        type: String,
        default: 'Click'
      },
      path: {
        type: String,
        default: '#'
      }
    },
  })
</script>

<style scoped>

</style>
