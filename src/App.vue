<template>
  <div id="app">
    <router-view/>
  <Tabbar />
  </div>
</template>
<script>
    import Tabbar from '@/components/tabBar.vue'
    export default {
      components:{
        Tabbar
      }
    }
</script>
<style>
html,body{
  margin: 0;
}
body{
  font-size: 16px;
}



</style>
