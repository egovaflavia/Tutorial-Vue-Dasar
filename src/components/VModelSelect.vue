<script setup>
import { ref } from "vue"

const city = ref("")
</script>

<template>
  <select v-model="city">
    <option disabled value="">-- Pilih Kota --</option>
    <option>Jakarta</option>
    <option>Bandung</option>
    <option>Surabaya</option>
  </select>

  <p>Kota dipilih: {{ city }}</p>
</template>
