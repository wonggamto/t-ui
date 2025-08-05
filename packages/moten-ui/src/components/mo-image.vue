<script setup lang="ts">
import { ref } from "vue";

defineProps<{ src: string }>();
const str = ref("11111");
console.log(str);
</script>

<template>
  <img :src="src" class="image" />
</template>

<style scoped>
.image {
  width: 300px;
  height: 200px;
  margin: 0 auto;
}
</style>
