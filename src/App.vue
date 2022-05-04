<template>
  <headerView/>
  <router-view/>
</template>
<script>
import headerView from '@/views/header.vue'
export default {
  components: {
    headerView,
  }
}
</script>
<style global>
@import './assets/css/common.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
