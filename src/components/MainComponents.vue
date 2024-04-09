<template>
   <main>
        <img src="/img/avatar_2.jpg" alt="immagine">
        <CardComponents/>
   </main>
</template>

<script>
    import CardComponents from './CaruselComp.vue/CardComponents.vue'
    export default {
        name: 'MainComponents',
        components: {
          CardComponents,
        },
        data() {
          return {
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>