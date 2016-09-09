<template>
  <div class="content-right">
    <desc-card></desc-card>
  </div>
</template>

<script>
import DescCard from './right/DescCard'

export default {
  components: {
    DescCard
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-right{
  width: 220px ;
  margin: 20px 0 0 20px;
  height:500px;
  float: left;
}
</style>
