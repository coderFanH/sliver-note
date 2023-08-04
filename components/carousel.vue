<script setup lang="ts">
import { NCarousel } from 'naive-ui';
const porps = defineProps<{
  autoplay: false
  direction: 'horizontal'
  draggable: false
  arrow: false
}>()
</script>

<template>
  <div>
    <n-carousel :autoplay="porps.autoplay" :direction="porps.direction" :draggable="porps.draggable" :show-arrow="porps.arrow">
      <slot></slot>
    </n-carousel>
  </div>
</template>

<style scoped></style>