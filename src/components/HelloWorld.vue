<script setup>
  const getMock = () => {
      var loginMode = 'msdk';//游戏内默认msdk(wx|qq|msdk)
      var url = '/api/msdk/proxy/query_common_credit';
      this.$axios.get(url)
        .then(response => {
          
        })
        .catch(error => {
          
        })
    
  }
</script>

<template>
 <button @click="getMock"></button>
</template>

<style scoped>
</style>
