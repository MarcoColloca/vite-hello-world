<script>
    export default{
        data() {
            return {
                title: ` Titolo dell'Hero `,
            }
        },       
    }
</script>



<template>
    <div>
        <div class="hero__section">
            
            <h1 class="hero-title">
              {{ title }}
            </h1>
            <img class="hero__image" src="../assets/Cosmic Dream.jpg" alt="">
        </div>
    </div>
</template>



<style scoped>
    .hero-title{
        color: rgb(30, 14, 255);
        font-size: 40px;
        text-align: center;
        margin-bottom: 75px;
    }

    .hero__section{
        height: 100vh;
        width: 100%;
        padding: 100px 0;
        background-color: rgb(0, 0, 0);
        position: relative;
    }

    .hero__image{
        max-width: 100%;
        aspect-ratio: 1/1;
    }
</style>