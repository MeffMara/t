<template>
  <nav>
    <ul class="d-flex p-1">
      <li v-for="item in menuItems" :key="item.name">
        <a href="#">{{ item.name }}</a>
      </li>
    </ul>
  </nav>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'NavItem',

  data() {
    return {
      menuItems: [
        {
          name: 'About us',
        },
        {
          name: 'Vacancies',
        },
        {
          name: 'Offers',
        },
        {
          name: 'Working principles',
        },
        {
          name: 'Contacts',
        },
      ],
    }
  },
})
</script>
