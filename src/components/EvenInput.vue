<script setup>
import { ref } from 'vue'
const name = ref('')
</script>

<template>
  <div>
    <input v-model="name" placeholder="Ketik Nama" />
    <p>Hello {{ name }}</p>
  </div>
</template>

