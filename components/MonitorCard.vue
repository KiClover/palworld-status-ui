<script lang="ts" setup>


</script>

<template>
<a-card title="服务器资源监控">
<div>
  <a-row>
    <a-col :span="2"><h5 align="left">CPU负载:</h5></a-col>
    <a-col :span="10">
      <a-tag color="green" align="left">
      <template #icon>
        <icon-check-circle-fill />
      </template>
      运行正常
    </a-tag></a-col>
    <a-col :span="12"><a-progress percent="0.9" /></a-col>
  </a-row>
</div>
</a-card>
</template>

<style scoped>
.card-item {
  display: flex;
  justify-content: space-between;
  padding: 15px 0;
  border-bottom: 1px solid rgb(229, 230, 235);
  &-title {
    color: $primary-font-color;
  }
  &-desc {
    color: $secondary-font-color;
  }
  &-button {
    color: $secondary-font-color;
    text-align: right;
  }
}
</style>
