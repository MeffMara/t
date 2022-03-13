<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col-2 d-flex">
          <img src="/svg/logo-man.svg" alt="logo" />
          <img src="/svg/logo-text.svg" alt="text" />
        </div>
        <div class="col-7">
          <NavItem />
        </div>
        <div class="col-3 d-flex">
          <a href="mailto:info@zubi-solutions.de" class="button">
            <img src="/svg/mail.svg" alt="mail" />
            info@zubi-solutions.de
          </a>
          <a href="tel:+49(0)1712889680" class="button button--gray">
            <img src="/svg/phone.svg" alt="phone" />
            +49 (0) 171 288 96 80
          </a>
        </div>
      </div>
      This is header {{ pages }}
    </div>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'
import NavItem from '@/components/NavItem/index.vue'

export default Vue.extend({
  name: 'AppHeader',
  components: {
    NavItem,
  },
  props: {
    pages: {
      type: String,
      default: ''
    },
  },
})
</script>
