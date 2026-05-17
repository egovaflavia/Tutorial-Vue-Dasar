<script setup>
import { ref, computed } from "vue"

const age = ref(20)

const status = computed(() => {
  return age.value >= 18 ? "Dewasa" : "Anak-anak"
})
</script>

<template>
  <p>Umur: {{ age }}</p>
  <p>Status: {{ status }}</p>
</template>
