<script setup lang="ts">
  import { ref } from 'vue';

  const number = ref<number>(0);
</script>

<template>
  <div>
    <p>Home page with 'ref-zero' {{ number }}</p>
  </div>
</template>
