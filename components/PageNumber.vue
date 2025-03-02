<template>
  <p class="custom-page-number mb-0"> หน้า {{ props.page }} </p>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
  page: {
    type: Number,
    default: 1,
  }
})
</script>

<style>
.custom-page-number {
  font-size: 12px  !important;
  position: absolute !important;
  margin: 0 !important;
  bottom: 0 !important;
  right: 0 !important;
  margin-right: 28px !important;
  margin-bottom: 4px !important;
}
</style>