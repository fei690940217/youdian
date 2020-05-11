<template>
  <div class="home">
  <Topbar class="qingqing"></Topbar>
  </div>
</template>

<script>
// @ is an alias to /src
import Topbar from '@/components/topbar.vue'

export default {
  name: 'Home',
  components: {
    Topbar
  }
}
</script>
<style scoped>
.qingqing >>> .h4{
  font-size: 2rem;
}
</style>
