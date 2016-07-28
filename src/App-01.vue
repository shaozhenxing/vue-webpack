<template>
  <h3 @click="click()">{{ msg }}</h3>
  <app0101></app0101>
</template>

<script>
import app0101 from './App-01-01.vue'

module.exports = {
    data:function(){
        return{
            msg:'儿子5'
        }
    },
    components:{app0101},
    methods:{
        click:function(){
             this.$broadcast('grandson','爸爸被点击了1');
        }
    }
}
</script>

<style scoped>
h3{
  color:dodgerblue;
}
</style>