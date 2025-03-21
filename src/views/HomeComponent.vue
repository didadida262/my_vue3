<template>
  <div class="w-[200px] h-[200px] bg-[green]">
    {{ msg }}
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const msg = ref('vue3_template')
</script>
