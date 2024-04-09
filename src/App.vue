<script>
    export default{
        data() {
            return {
                message: '(ง•̀_•́)ง',
            }
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
            </h1>            
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