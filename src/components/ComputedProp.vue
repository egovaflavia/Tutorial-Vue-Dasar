<script setup>
import { ref, computed } from "vue"

const firstName = ref("Budi")
const lastName = ref("Santoso")

const fullName = computed(() => {
  return firstName.value + " " + lastName.value
})
</script>

<template>
  <p>Nama Lengkap: {{ fullName }}</p>
</template>
