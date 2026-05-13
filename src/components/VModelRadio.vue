<script setup>
import { ref } from "vue"

const gender = ref("")
</script>

<template>
  <div>
    <label>
      <input type="radio" value="Laki-laki" v-model="gender" /> Laki-laki
    </label>
    <label>
      <input type="radio" value="Perempuan" v-model="gender" /> Perempuan
    </label>
    <p>Jenis Kelamin: {{ gender }}</p>
  </div>
</template>
