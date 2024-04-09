<template>
    <div>
        <h1>Card Component</h1>
        <img :src="img" alt="immagine">
    </div>
</template>

<script>
    export default {
        name: 'CardComponent',
        data(){
            return {
                img: '/images/03.jpg'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>