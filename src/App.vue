<template>
  <div id="app">
    <!--<div class="content">
      <router-link to="/goods">商品</router-link>
      <router-link to="/ratings">评论</router-link>
      <router-link to="/seller">商家</router-link>
    </div>
    <router-view></router-view>-->
    <Login/>
  </div>
</template>

<script>
import Login from './components/login'
export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
