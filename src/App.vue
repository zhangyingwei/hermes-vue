<template>
  <div id="app">
    <nav-head></nav-head>
    <container></container>
  </div>
</template>

<script>
import Hello from './components/Hello'
import NavHead from './components/nav/NavHead'
import Container from './components/Container/Container'

export default {
  components: {
    Hello,
    NavHead,
    Container
  }
}
</script>

<style>
@import './assets/css/main.css';
@import './assets/bootstrap/css/bootstrap.min.css';

html {
  height: 100%;
}
body{
  padding: 0;
  margin: 0;
  background-color: #F2F2F2;
  font-family: '微软雅黑'
}
</style>
