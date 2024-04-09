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
    <div>
        <div>
            <h1 class="title">
              {{ title }}
            </h1>            
        </div>
    </div>
</template>



<style scoped>
  .title{
    color: crimson;
    font-size: 50px;
    text-align: center;
  }
</style>