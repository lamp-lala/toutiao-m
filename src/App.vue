<template>
  <div id="app">
    <!-- 路由的出口，不能删 -->
    <router-view />
   <login></login>
  </div>
</template>
<script>
import login from './views/login/index.vue'
export default {
  name: "App",
  components:{
    login,
  }
};
</script>


<style lang="less">
</style>
