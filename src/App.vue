<template>
  <h1>{{ msg }}</h1>
  <app-01></app-01>
</template>

<script>

import app01 from './App-01.vue'

module.exports = {
    data:function(){
        return{
            msg:'父亲1'
        }
    },
    components:{app01}
}

</script>

<style scoped>
h1 {
  color: red;
}
</style>