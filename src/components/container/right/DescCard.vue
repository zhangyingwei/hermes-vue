<template>
  <div class="content-right-desc">
    <div class="desc">{{desc}}</div>
    <div class="desc-button">
      <button v-for="button in buttons" type="button" class="btn {{button.className}} btn-block">{{button.text}}</button>
    </div>
    <div class="copyright text-center">
      <div>{{copyright.info}}</div>
      <div><a href="{{copyright.recored.link}}" target="_blank">{{copyright.recored.text}}</a></div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      desc: 'hermes，一个技术类博客内容的聚集地。',
      buttons: [{
        text: '我要订阅',
        className: 'btn-info'
      }, {
        text: '我要贡献',
        className: 'btn-danger'
      }],
      copyright: {
        info: '©2016 hermes',
        recored: {
          text: '京ICP备15037338号-1',
          link: 'http://www.miitbeian.gov.cn/'
        }
      }
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content-right-desc{
  background-color: #fff;
  position:fixed;
  width: 220px;
}
.content-right-desc div{
  padding: 15px;
}
.content-right-desc .desc{
  font-size: 15px;
  font-weight: bolder;
  border-bottom: 1px dashed #007fff;
}
/*版权信息*/
.content-right-desc .copyright{
  font-size: 13px;
  font-weight: bolder;
  border-top: 1px dashed #007fff;
  color: #B2B2B2;
}
.content-right-desc .copyright div{
  padding: 0;
}
.content-right-desc .copyright a{
  color: #B2B2B2;
}
.content-right-desc .desc-button{
  border: 0;
}
.content-right-desc .desc-button button{
  margin-left: 0;
}
</style>