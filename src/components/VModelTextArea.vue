<script setup>
import { ref } from "vue"

const message = ref("")
</script>

<template>
  <div>
    <textarea v-model="message" placeholder="Tulis pesan..."></textarea>
    <p>Pesan: {{ message }}</p>
  </div>
</template>
