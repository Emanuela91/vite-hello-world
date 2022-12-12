<script>
export default{
    data() {
        return{
            img: "/img/jumbo.png",
        };
    }
}
</script>

<template>
    <div>
        <img :src="img" alt="hero">
    </div>
</template>

<style scoped>
    img{
        width: 100%;
    }
</style>