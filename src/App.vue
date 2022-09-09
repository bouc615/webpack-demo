<template>
  <div>
    hello, {{name}}
  </div>
</template>

<script setup lang="ts">
  import {ref} from 'vue'
  const name = ref<string>('bouc')

  console.log('name:', name)
</script>