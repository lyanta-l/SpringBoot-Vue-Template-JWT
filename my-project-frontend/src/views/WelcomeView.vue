<script setup lang="ts">

</script>

<template>
  <div style="width: 100vw; height: 100vh;overflow: hidden;display: flex">
    <div style="flex: 1;background-color: black">
      <el-image style="width: 100%;height: 100%" fit="cover"
      src="https://images.unsplash.com/photo-1439405326854-014607f694d7?w=1920&q=80"/>
    </div>
    <div class="right-card">
      <router-view/>
    </div>
  </div>
</template>

<style scoped>
.right-card {
  width: 400px;
  z-index: 1;
  background-color: white;
}
</style>