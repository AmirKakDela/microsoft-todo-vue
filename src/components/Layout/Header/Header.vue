<script lang="ts" setup>
import Search from './Search.vue';
import ControlPanel from './ControlPanel.vue';
</script>
<template>
  <div class="header">
    <div class="header__logo">To Do</div>
    <Search></Search>
    <ControlPanel></ControlPanel>
  </div>
</template>
<style lang="less">
.header {
  width: 100%;
  height: 45px;
  background-color: #0078D7;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 20px;

  &__logo {
    color: white;
    font-weight: 700;
    font-size: 18px;
  }
}
</style>
