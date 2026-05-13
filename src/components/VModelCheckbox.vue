<script setup>
import { ref } from "vue"

const agree = ref(false)
</script>

<template>
  <label>
    <input type="checkbox" v-model="agree" />
    Saya setuju
  </label>
  <p>Status: {{ agree }}</p>
</template>
