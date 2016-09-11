<template>
  <div class="content-left">
    <left-nav></left-nav>
  </div>
</template>

<script>
import LeftNav from './left/LeftNav'

export default {
  components: {
    LeftNav
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-left{
  width: 140px;
  margin: 20px 0 0 0;
  /*background-color: #fff;*/
  height:500px;
  float: left;
}
</style>
