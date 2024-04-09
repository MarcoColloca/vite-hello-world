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
        
        <AppTitle></AppTitle>

        <AppHero></AppHero>
        
    </div>
</template>


<style>

</style>