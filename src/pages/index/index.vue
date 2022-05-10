<template>
  <view class="text">
    <text>{{ title }}</text>
  </view>
</template>

<script setup lang="ts">
import { ref } from "vue";
console.log(process.env.VUE_APP_BASE_URL);
let title = ref("");
</script>

<style lang="scss" scoped>
.text {
  text {
    color: red;
  }
}
</style>
