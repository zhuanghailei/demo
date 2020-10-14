<template>
  <div id="home">
    <!--  导航  -->
    <nav-bar class="nav">
      <div slot="center">购物街</div>
    </nav-bar>
    <!--  轮播图  -->

  </div>
</template>

<script>
  import NavBar from "components/common/navbar/NavBar"

  export default {
    name: "Home",
    components: {
      NavBar
    }
  }
</script>

<style scoped>
  .nav{
    background: pink;
  }
</style>
