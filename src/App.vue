<script setup lang="ts"></script>

<template>
  <div class="app">App</div>
</template>

<style scoped>
  .app {
    background: red;

    &:hover {
      background: green;
    }

    opacity: 0; /* Remove this line to get it works again */
  }
</style>
