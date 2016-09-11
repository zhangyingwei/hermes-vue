<template>
  <div class="content-left-nav">
    <ul>
      <li class="text-blue text-left"  v-for="nav in navs" >{{nav.text}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      navs: [
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: '推荐'},
        {text: 'java'},
        {text: '前端'},
        {text: 'PHP'},
        {text: 'Redis'}
      ]
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-left-nav {
  /*position:fixed;*/
  width: 140px;
}
.content-left-nav ul{
  padding: 0;
}
.content-left-nav ul li{
  list-style: none;
  font-size: 18px;
  padding: 5px 0;
  margin: 0;
  border-bottom: 1px dashed #007fff;
}
.content-left-nav ul li:hover{
  background-color: #f1f1f1;
  cursor: pointer;
}
</style>