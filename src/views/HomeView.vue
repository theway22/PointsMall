<template>
  <div class="home">
    <header>首页</header>
  </div>
</template>

<script>
import axios from 'axios';

// @ is an alias to /src

export default {
  components: {
    
  },
  created(){
    // axios.get("http://kumanxuan1.f3322.net:8881/cms/products/recommend")
    // .then(res=>{
    //   console.log(res.data);
    // })
  }
}

</script>

<style scoped>
  header{
    background-color: pink;
  }
</style>
