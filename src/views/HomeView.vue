<template>
  <HomeHeader />
  <HomeBody />
  <HomeFooter />
</template>

<script>
import HomeHeader from '../molecules/HomeHeader.vue'
import HomeBody from '../molecules/HomeBody.vue'
import HomeFooter from '../molecules/HomeFooter.vue'

export default {
  name: 'HomeView',
  components: {
    HomeHeader,
    HomeBody,
    HomeFooter
  }
  }
</script>
