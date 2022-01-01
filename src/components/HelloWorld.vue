<script setup lang="ts">
import BaseButton from '@/components/BaseComponents/BaseButton.vue'
import BaseInput from '@/components/BaseComponents/BaseInput.vue'
import { ref,Ref } from 'vue';

const texto:Ref<string> = ref('')


</script>

<template>
<div class="body">
  <BaseButton text="hola"/>
  <BaseInput v-model="texto" :max="10"/>

</div>
</template>

<style scoped lang="scss">
$font-stack: times;
$primary-color: red;

.body {
  font: 100% $font-stack;
  color: $primary-color;
}
</style>
