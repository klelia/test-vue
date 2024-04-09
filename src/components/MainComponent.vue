<template>
    <main>
        <img src="../assets/img/03.jpg" alt="immagine">
        <CardComponent />
    </main>
    

</template>

<script>
    import CardComponent from './carouselComponents/CardComponent.vue';
    export default {
        name: 'MainComponent',
        components:{
            CardComponent
        },
        data(){
            return {
                
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>