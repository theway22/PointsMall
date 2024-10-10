<template>
  <div id="app">
    <TopBar></TopBar>
    <Header></Header>
    <router-view/>
    <Footer></Footer>
  </div>
</template>

<script>
import TopBar from './components/TopBar.vue';
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
  export default{
    components:{
      TopBar,
      Header,
      Footer
    }
  }
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
