<script>
    import { defineAsyncComponent } from 'vue'


    export default{
        data() {
            return {
                message: '(ง•̀_•́)ง',
            }
        },

        components:{
            "AppTitle": defineAsyncComponent(() => import ('./components/AppTitle.vue')),
            "AppHero": defineAsyncComponent(() => import ('./components/AppHero.vue'))
        },

        methods: {
            sayHello(){
                console.log('hello')
            }
        }
    }
</script>

<template>
    <div>
        <div>
            <h1 class="title">
              {{ message }}  
              A          
            </h1>    
            <AppTitle></AppTitle>
            <AppHero></AppHero>
        </div>
    </div>
</template>


<style>
  .title{
    color: crimson;
    font-size: 50px;
    text-align: center;
  }
</style>