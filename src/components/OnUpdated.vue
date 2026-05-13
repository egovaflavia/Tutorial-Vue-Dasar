<script setup>
import { ref, onUpdated } from 'vue'

const count = ref(0)

onUpdated(() => {
  console.log("Komponen sudah diperbarui count: ", count.value)
})
</script>

<template>
  <div>
    <hr>
    <h1>OnUpdated</h1>
    <button @click="count++">Increment</button>
    <p>Count: {{ count }}</p>
  </div>
</template>