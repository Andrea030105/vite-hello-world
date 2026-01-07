<script>
export default {
    data() {
        return {
            img:'/public/jumbo.png'
        }
    },
}
</script>
<template>
    <div>
        <img :src="img" > 
    </div>
</template>
<style scoped>
    img{
        width: 100%;
    }
</style>