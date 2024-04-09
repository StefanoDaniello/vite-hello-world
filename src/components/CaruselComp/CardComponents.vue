<template>
    <div @click="change">
        <h2>Nome: {{ sttitles }}</h2>
        <img :src="img" alt="immagine">
    </div>
</template>

<script>
    export default {
        name: 'CardComponents',
        props: ['sttitles', 'numero'],
        data() {
          return {
            img: '/img/avatar_' + (this.numero + 1) + '.jpg'
          }
        },
        methods: {
          change () {
            this.img = '/img/avatar_io.jpg'
        }
      }
    }
</script>

<style lang="scss" scoped>

</style>