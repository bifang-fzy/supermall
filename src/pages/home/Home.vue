<template>
  <div id="Home">
      <nav-bar class="home_nav"><div slot="center">购物街</div></nav-bar>
  </div>
</template>

<script>
import NavBar from 'components/common/navbar/NavBar'

export default {
  name: 'Home',
  components: {
    NavBar
  }
}
</script>

<style scoped>
  .home_nav{
    width: 100%;
    background: palevioletred;
    color: #fff;
    position: fixed;
    left: 0px;
    top: 0px;
    z-index: 99;
    box-shadow: 0px 2px 10px #eee;
    font-size: 15px;
  }
</style>