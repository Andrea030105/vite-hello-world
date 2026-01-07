<script>
export default {
    data(){
        return{
            title:'La mia prima app con Vite!!',
        }
    }
}
</script>
<template>
    <div class="main">
       {{ title }} 
    </div>
</template>
<style scoped>
    .main{
        color: red;
        font-size: 2rem;
        font-weight: bold;
    }
</style>