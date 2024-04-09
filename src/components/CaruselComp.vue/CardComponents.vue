<template>
    <div>
        <h1>Card</h1>
        <img :src="img" alt="immagine">
    </div>
</template>

<script>
    export default {
        name: 'CardComponents',
        data() {
          return {
            img: '/img/avatar_2.jpg'
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>