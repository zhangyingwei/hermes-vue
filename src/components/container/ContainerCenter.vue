<template>
  <div class="content-center">
    <div class="content-box" v-for="box in boxs" >
      <div class="box-title">
        <div class="box-title-kind float-left">{{box.title.kind}}</div>
        <div class="box-title-desc text-blue float-right">{{box.title.desc}}</div>
      </div>
      <div class="box-list">
        <ul>
          <li v-for="list in box.lists" >
            <div class="float-left list-img">
              <!--<img src="">-->
            </div>
            <div class="list-desc float-left">
              <div class="title">{{list.title}}</div>
              <div class="meta" >
                <ul>
                  <li>{{list.meta.author}}</li>
                  <li>{{list.meta.time}}</li>
                </ul>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      boxs: [{
        title: {
          kind: '小编推荐',
          desc: '订阅'
        },
        lists: [{
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }, {
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }]
      }, {
        title: {
          kind: 'java',
          desc: '查看更多'
        },
        lists: [{
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }, {
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }]
      }, {
        title: {
          kind: '前端',
          desc: '查看更多'
        },
        lists: [{
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }, {
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }]
      }, {
        title: {
          kind: 'PHP',
          desc: '查看更多'
        },
        lists: [{
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }, {
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }]
      }, {
        title: {
          kind: 'Redis',
          desc: '查看更多'
        },
        lists: [{
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }, {
          title: '一套完整的Android通用框架',
          meta: {
            author: '张英伟的博客',
            time: '2016-09-12'
          }
        }, {
          title: '几种常见Dialog，直接拿去用！懒人必收',
          meta: {
            author: 'Weavey',
            time: '2016-09-12'
          }
        }]
      }]
    }
  }
}
</script>
  

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.content-center{
  width: 600px;
  margin: 20px 0 0 20px;
  /*background-color: #fff;*/
  height:1500px;
  float: left;
}
.content-box{
  background-color: #fff;
  margin-bottom: 20px;
}
/* box title */
.box-title{
  padding: 10px 20px;
  border-bottom: 1px solid #F1F1F1;
  font-weight: bold;
}
.box-title .box-title-desc{
  cursor: pointer;
}
/*list*/
.box-list{
  padding: 20px;
}
.box-list ul{
  list-style: none;
  padding: 0;
  margin: 0;
}
.box-list ul li{
  margin: 10px 0 0 0;
}
.box-list .list-img{
  width: 70px;
  height: 70px;
  background-color: #f1f1f1;
}
.box-list .list-desc {
  padding: 10px;
}
.box-list .list-desc .title{
  font-size: 18px;
  font-weight: bolder;
}
.box-list .list-desc .meta{
  
}
.box-list .list-desc .meta ul li{
  float: left;
  padding:0 5px 0 0;
  font-size: 13px;
  color: #a9a9a9;
}
</style>
