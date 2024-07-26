<template>
  <div>
    <!-- <NuxtPage></NuxtPage> -->
    <nuxt-link to="/">首页</nuxt-link>
    <nuxt-link to="/login">登录</nuxt-link>
    <NuxtPage></NuxtPage>
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: "开心超人",
  description: "一个超级开心的人",
  keywords: "开心,超人 ，抽象的空中超人",
});
</script>

<style lang="less" scoped></style>
