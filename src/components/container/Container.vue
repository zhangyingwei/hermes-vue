<template>
  <div class="content-main over-flow">
    <container-left></container-left>
    <container-center></container-center>
    <container-right></container-right>
  </div>
</template>

<script>
import ContainerLeft from './ContainerLeft'
import ContainerCenter from './ContainerCenter'
import ContainerRight from './ContainerRight'

export default {
  components: {
    ContainerLeft,
    ContainerCenter,
    ContainerRight
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-main{
  width: 1000px;
  margin: 4em auto 0 auto;
}
</style>
