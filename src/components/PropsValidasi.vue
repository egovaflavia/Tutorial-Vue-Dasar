<script setup>
defineProps({
  age: {
    type: Number,
    required: true
  }
})
</script>

<template>
  <p>Umur saya {{ age }} tahun</p>
</template>
