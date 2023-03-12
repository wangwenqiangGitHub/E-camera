<script setup lang="ts">
// 全局异步，需要用Suspense
var devices = await navigator.mediaDevices.enumerateDevices()
</script>

<template>
    <main>{{ devices }}</main>
</template>

<style lang="scss"></style>
