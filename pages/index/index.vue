<!--  -->
<template>
  <MyHeader :ceshi="123"></MyHeader>
  <div class="container">
    <van-button type="primary">主要按钮</van-button>
    <van-button type="success">成功按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
  </div>
</template>

<script setup>
const { data } = useFetch("http://127.0.0.1:3000/api/data");
console.log("数据：", data);
</script>

<style lang="scss" scoped></style>
