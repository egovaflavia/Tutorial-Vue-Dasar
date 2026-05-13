<script setup>
import { ref, onMounted } from "vue"

const inputEl = ref(null)

onMounted(() => {
  inputEl.value.focus()
})
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-14 01:05:05 
 * @Desc: Template Refs digunakan untuk mendapatkan akses langsung ke element DOM atau child component, biasanya digunakan untuk melakukan manipulasi DOM atau memanggil method pada child component. Pada contoh ini kita menggunakan template refs untuk memfokuskan input ketika halaman dimuat. 
 */
<template>
  <input ref="inputEl" placeholder="Auto focus saat mount" />
</template>
