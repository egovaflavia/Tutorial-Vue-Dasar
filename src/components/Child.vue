<script setup>
import { ref } from "vue"

function sayHello() {
  alert("Halo dari Child Component!")
}

defineExpose({ sayHello })
</script>

<template>
  <p>Ini komponen anak</p>
</template>
