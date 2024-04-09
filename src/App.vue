<script>
    import { defineAsyncComponent } from 'vue'

    /* Versione Standard di importazione componenti (Continua...)
     import AppTitle from './components/AppTitle.vue';
     import AppHero from './components/AppHero.vue';
    */


    export default{
        data() {
            return {
                message: '(ง•̀_•́)ง',
            }
        },

        components:{
            "AppTitle": defineAsyncComponent(() => import ('./components/AppTitle.vue')),
            "AppHero": defineAsyncComponent(() => import ('./components/AppHero.vue')),

            /* (...continua) Versione Standard di importazione componenti
             AppHero,
             AppTitle,
            */
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