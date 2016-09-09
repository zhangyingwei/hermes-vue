<template>
  <div class="nav-head">
    <div class="nav-content clearfix">
      <ul >
        <li>
          <!--<span class="text-blue text-title">{{title}}</span>-->
          <span class="img-nav-logo"><img src="../../assets/img/logo.png"></span>
        </li>
        <li class="action">
          <span class="text-blue text-title text-line">{{title}}</span><span class="text-blue">{{desc}}</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'Hermes',
      desc: '专业狙击技术类博客'
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-head {
  width: 100%;
  height: 4em;
  border-bottom: 1px solid #f0f0f0;
  background-color: #fff;
  position:fixed;
  top:0;
  left:0;
}
.nav-head .img-nav-logo{
  margin-right: 40px;
}
.nav-head .img-nav-logo img{
  width: 30px;
}
.nav-head .nav-content {
  width: 1000px;
  margin: 0 auto;
  margin-top: 10px;
}
.nav-head ul{
  height: 100%;
  padding: 0;
}
.nav-head ul li{
  list-style: none;
  float: left;
  overflow: hidden;
  margin:0 auto;
}
.nav-head .text-title{
  font-size: 1.5em;
  font-weight: 1em;
  margin-right: 0.5em;
}

</style>
