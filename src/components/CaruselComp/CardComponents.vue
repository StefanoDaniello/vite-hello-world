<template>
    <div>
        <h2>{{ sttitles }}</h2>
        <img :src="img" alt="immagine">
    </div>
</template>

<script>
    export default {
        name: 'CardComponents',
        props: ['sttitles'],
        data() {
          return {
            img: '/img/avatar_2.jpg'
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>