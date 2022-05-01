<script setup lang="ts">
</script>

<template>
  <div>
    Route 1
    <input type="range" class="base-range">
  </div>
</template>

<style scoped>
  .base-range {
    -webkit-appearance: none;

    &::-webkit-slider-runnable-track {
      background: red;

      &:hover {
        background: green;
      }

      opacity: 0;
    }
  }
</style>
