<template>
  <h6>{{msg}}</h6>
</template>

<script>

module.exports = {
    data:function(){
        return{
            msg:'孙子1'
        }
    },
    events:{
        grandson:function(data){
            alert(data);
        }
    }
}

</script>

<style scoped>
h6 {
  color:darkmagenta;
}
</style>