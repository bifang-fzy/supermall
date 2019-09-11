<template>
    <div id="publicTabbar">
        <tabBar>
            <tabBarItem path='/home' activeColor="#e25858">
                <img slot="item-icon" src="@/assets/img/tabbar/home.png" alt="" />
                <img slot="item-icon-active" src="@/assets/img/tabbar/home_active.png" alt="" />
                <div slot="item-text">首页</div>
            </tabBarItem>
            <tabBarItem path='/category' activeColor="#e25858">
                <img slot="item-icon" src="@/assets/img/tabbar/category.png" alt="" />
                <img slot="item-icon-active" src="@/assets/img/tabbar/category_active.png" alt="" />
                <div slot="item-text">分类</div>
            </tabBarItem>
            <tabBarItem path='/cart' activeColor="#e25858">
                <img slot="item-icon" src="@/assets/img/tabbar/cart.png" alt="" />
                <img slot="item-icon-active" src="@/assets/img/tabbar/cart_active.png" alt="" />
                <div slot="item-text">购物车</div>
            </tabBarItem>
            <tabBarItem path='/profile' activeColor="#e25858">
                <img slot="item-icon" src="@/assets/img/tabbar/profile.png" alt="" />
                <img slot="item-icon-active" src="@/assets/img/tabbar/profile_active.png" alt="" />
                <div slot="item-text">我的</div>
            </tabBarItem>
        </tabBar>
    </div>
</template>

<script>
import tabBar from './tabBar'
import tabBarItem from './tabBarItem'

export default {
  name: 'publicTabbar',
  components: {
    tabBar,
    tabBarItem
  }
}
</script>

<style scoped>
.tab_bar_item img{
    width: 25px;
    height: 25px;
    vertical-align: middle;
}
</style>