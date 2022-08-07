<script setup lang="ts">
import Header from './Header/Header.vue';
import Sidebar from './Sidebar.vue';
</script>
<template>
  <Header></Header>
  <div class="main-container">
    <Sidebar></Sidebar>
    <div>main</div>
  </div>
</template>
<style lang="less">
.main-container {
  display: flex;
  //45px - высота header
  height: calc(100% - 45px);
}
</style>
