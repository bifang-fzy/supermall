<template>
  <div id="TabBar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'TabBar'
}
</script>

<style scoped>
#TabBar{
    width: 100%;
    background: #fff;
    box-shadow: 0px -2px 10px #eee;
    position: fixed;
    left: 0px;
    bottom: 0px;
    z-index: 99;
    display: flex;
    padding: 5px 0px;
}
</style>