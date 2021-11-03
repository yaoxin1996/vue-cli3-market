<template>
  <div id="tabbar">
    <tabbar-item>
      <template v-slot:item-icon>
        <img src="@/assets/img/tabbar/home.png" alt="">
      </template>
      <template v-slot:item-text>
        <div>首页</div>
      </template>
    </tabbar-item>
    <tabbar-item>
      <template v-slot:item-icon>
        <img src="@/assets/img/tabbar/home.png" alt="">
      </template>
      <template v-slot:item-text>
        <div>首页</div>
      </template>
    </tabbar-item>
    <tabbar-item>
      <template v-slot:item-icon>
        <img src="@/assets/img/tabbar/home.png" alt="">
      </template>
      <template v-slot:item-text>
        <div>首页</div>
      </template>
    </tabbar-item>
    <tabbar-item>
      <template v-slot:item-icon>
        <img src="@/assets/img/tabbar/home.png" alt="">
      </template>
      <template v-slot:item-text>
        <div>首页</div>
      </template>
    </tabbar-item>

  </div>
</template>
<script>
import TabbarItem from './tabbarItem.vue'
export default {
  components: {
    TabbarItem
  }
}
</script>
<style scoped>
#tabbar {
  height: 49px;
  background: #f7f7f7;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow: 0 -2px 2px rgba(0, 0, 0, .1);
  display: flex;
}
img {
  width: 24px;
  height: 24px;
  margin-top: 3px;
  margin-bottom: 2px;
}
</style>
