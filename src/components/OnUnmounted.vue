<script setup>
import { onUnmounted } from "vue"

onUnmounted(() => {
  console.log("Komponen sudah dihapus dari DOM")
})
</script>

<template>
 <div>
    <hr>
    <p>Komponen ini bisa di-unmount</p>
 </div>
</template>
