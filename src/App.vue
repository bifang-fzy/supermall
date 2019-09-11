<template>
  <div id="app">
    <router-view></router-view>
    <pubilcTabbar></pubilcTabbar>
  </div>
</template>

<script>
import pubilcTabbar from 'components/common/pubilcTabbar/PublicTabbar'

export default {
  name: 'app',
  components: {
    pubilcTabbar
  }
}
</script>

<style>
@import './assets/css/base.css';
</style>
