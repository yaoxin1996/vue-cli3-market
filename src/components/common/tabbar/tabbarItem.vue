<template>
  <div class="tabbar-item">
    <div>
      <slot name="item-icon"></slot>
    </div>
    <slot name="item-text"></slot>
  </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.tabbar-item {
  flex: 1;
  font-size: 14px;
  text-align: center;
}
</style>
