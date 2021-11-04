<template>
  <div class="home">
    <Banner></Banner>
    <Footer></Footer>
  </div>
</template>

<script>
  // 引入组件
  import Banner from './components/banner.vue'
  import Footer from './components/footer.vue'

  //  引入css
  import './assets/css/bootstrap.css'
  import './assets/css/style.css'
  import './assets/css/swipebox.css'
  // title出现动画
  import 'animate.css'

  export default {
    name: 'App',
    components:{Banner,Footer}
  }
</script>

<style>
  
</style>
