<script setup lang="ts">
import { ref } from 'vue'
const counter = ref({
  count: 5
})

let { count } = counter.value
count++
</script>

<template>
  <main>
    <div>This is count  {{  counter.count }} {{ count }}</div>
  </main>
</template>
