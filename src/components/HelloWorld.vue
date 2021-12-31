<template>
  <BaseButton text="hola"/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BaseButton from '@/components/BaseComponents/BaseButton.vue'

export default defineComponent({
  
  props: {
    msg: String,
  },

  components: {
    BaseButton,
  },

});
</script>

<style scoped>

</style>
