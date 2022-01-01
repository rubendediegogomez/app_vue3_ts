<script setup lang="ts">
import { defineProps,Prototype } from 'vue';

defineProps({
  text: {
    type: String as Prototype<string>,
    required:true
  }
})

</script>

<template>
  <button>{{ text }}</button>
</template>

<style scoped>

</style>