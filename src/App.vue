<template>
  <h1>{{ msg }}</h1>
  <app-01></app-01>
</template>

<script>
import app01 from './App-01.vue'
export default {
  data () {
    return {
      msg: 'Hello Vue!'
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