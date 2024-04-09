<script>

    export default{
        data(){
            return{
                title: 'La mia prima app con Vite!'
            }
        }
    }

</script>

<template>
    <h1 class="title">{{ title }}</h1>
</template>

<style>  
.title {
    font-size: 50px;
    color: red;
    display: flex;
}

</style>