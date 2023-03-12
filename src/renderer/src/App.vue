<script setup lang="ts">
// import Versions from './components/Versions.vue'
import Camera from './components/Camera.vue';

</script>

<template>
  <main class="">
    <Suspense>
      <Camera />
    </Suspense>
  </main>
  <el-button type="primary" size="default" @click="">445445</el-button>
  <div class="bg-red-500">hhhhhiiish</div>
</template>

<style lang="less">
@import './assets/css/styles.less';
</style>
