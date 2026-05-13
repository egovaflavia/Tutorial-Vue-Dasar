<script setup>
import { ref } from "vue"

const name = ref("")
</script>

<template>
  <div>
    <input v-model="name" placeholder="Ketik nama..." />
    <p>Halo, {{ name }}</p>
  </div>
</template>
