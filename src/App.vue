<template>
  <div id="app">
    <h1>今日头条</h1>
    <i class="toutiao toutiao-yanzhengma"></i>
    <van-button loading type="primary" />
    <van-button loading type="primary" loading-type="spinner" />
    <van-button loading type="info" loading-text="加载中..." />
    <router-view />
    <van-cell-group inset>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
  </div>
</template>

<script>
export default {
  // 给每个组件取个名字
  name: "App",
};
</script>

<style lang="less"></style>
