<template>
    <div>
        <h2>Nome: {{ sttitles }}</h2>
        <img :src="img + (numero + 1) + '.jpg'" alt="immagine">
    </div>
</template>

<script>
    export default {
        name: 'CardComponents',
        props: ['sttitles', 'numero'],
        data() {
          return {
            img: '/img/avatar_'
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>