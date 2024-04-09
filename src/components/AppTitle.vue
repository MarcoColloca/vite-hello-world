<script>
    export default{
        data() {
            return {
                title: 'La mia prima App con Vue!',
            }
        },       
    }
</script>



<template>
    <div class="title__section">
        <h1 class="title">
            {{ title }}
        </h1>            
    </div>
</template>



<style scoped>

    .title__section{
        background-color: darkslategrey;

    }

    .title{
        padding: 30px 0;
        color: crimson;
        font-size: 50px;
        text-align: center;
    }
</style>