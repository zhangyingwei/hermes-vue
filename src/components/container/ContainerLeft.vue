<template>
  <div class="content-left">
    {{desc}}
  </div>
</template>

<script>
export default {
  data () {
    return {
      desc: 'left'
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-left{
  width: 140px;
  margin: 20px 0 0 0;
  background-color: #fff;
  height:500px;
  float: left;
}
</style>
