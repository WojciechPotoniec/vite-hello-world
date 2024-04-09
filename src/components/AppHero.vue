<template>
    <div>
        <img :src="image" alt="Hero-image">
    </div>
</template>

<script>
    export default {
        name: "AppHero",
        data() {
            return {
                image: 'img/jumbo.png'
            }
        }
    }
</script>

<style scoped>
    img{
        width: 100%;
    }
</style>