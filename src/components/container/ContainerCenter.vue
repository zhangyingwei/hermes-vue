<template>
  <div class="content-center">
    {{desc}}
  </div>
</template>

<script>
export default {
  data () {
    return {
      desc: 'center'
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-center{
  width: 600px;
  margin: 20px 0 0 20px;
  background-color: #fff;
  height:1500px;
  float: left;
}
</style>
