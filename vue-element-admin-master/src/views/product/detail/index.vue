<template>
  <div class="app-container">
    <h2>商品详情页</h2>
  </div>
</template>

<script>
export default {
  name: 'ProductDetail',
  data() {
    return {
      productId: null
    }
  },
  created() {
    // 获取列表页传过来的 ID
    // this.productId = this.$route.query.productId;
    // console.log("当前商品ID:", this.productId);
  }
}
</script>

<style scoped>
/* 你的样式 */
</style>
