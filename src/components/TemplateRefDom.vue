<script setup>
import { ref, onMounted } from "vue"

const box = ref(null)

onMounted(() => {
  console.log("Lebar box:", box.value.offsetWidth, "px")
})
</script>

<template>
  <div ref="box" style="width: 200px; height: 100px; background: lightblue;">
    Kotak
  </div>
</template>
