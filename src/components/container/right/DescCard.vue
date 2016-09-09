<template>
  <div class="content-right-desc">
    <div class="desc">{{desc}}</div>
    <button type="button" class="btn btn-primary btn-block">Primary</button>
    <button type="button" class="btn btn-primary btn-block">Primary</button>
    <button type="button" class="btn btn-primary btn-block">Primary</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      desc: 'hermes，一个技术类博客内容的聚集地。'
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-right-desc{
  background-color: #fff;
}
.content-right-desc .desc{
  font-size: 15px;
  font-weight: bolder;
  padding: 15px;
}
</style>