<template>
   <main>
        <div v-for="(items , index) in titles " :key="items">
            <CardComponents :sttitles="items"/>
        </div>
   </main>
</template>

<script>
    import CardComponents from './CaruselComp/CardComponents.vue'
    export default {
        name: 'MainComponents',
        components: {
          CardComponents,
        },
        data() {
          return {
            titles:[
                'Stefano',
                'Lorenzo',
                'Michele',
                'Gennaro',
                'Davide'
            ]
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>