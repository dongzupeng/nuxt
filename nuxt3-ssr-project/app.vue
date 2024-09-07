<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup lang="ts">
</script>
<style>
body {
  background-color: #f0f0f0;
}
/* 设置滚动条 */
::-webkit-scrollbar {
  width: 4px;
  /* height: 5px; */
  background-color: #f0f0f0;
  border-radius: 10px;
}
/* 设置滚动条滑块 */
::-webkit-scrollbar-thumb {
  background-color: #c4c4c4;
  border-radius: 10px;
  transition: background-color 0.3s;
  &:hover {
    background-color: #a0a0a0;
  }
  &:active {
    background-color: #808080;
  }
}
</style>
