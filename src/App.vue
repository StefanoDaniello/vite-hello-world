<template>
  <HeaderComponents/>
  <MainComponents/>
</template>

<script>
  import HeaderComponents from './components/HeaderComponents.vue'
  import MainComponents from './components/MainComponents.vue'
  export default {
    name: 'App',
    components: {
      HeaderComponents,
      MainComponents,
    },
    data() {
      return {
      }
    },
  }
</script>

<style lang="scss" scoped>

</style>