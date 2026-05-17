<script setup>
import { ref, watch } from "vue"

const count = ref(0)

watch(count, (newVal, oldVal) => {
  console.log(`Count berubah dari ${oldVal} ke ${newVal}`)
})
</script>

<template>
  <button @click="count++">Tambah</button>
</template>
