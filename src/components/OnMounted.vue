<script setup>
import { ref, onMounted } from 'vue'

const message = ref('')

onMounted(() => {
  console.log("Komponen sudah tampil di DOM")
  message.value = "Halo dari onMounted!"
})
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-14 00:18:19 
 * @Desc: OnMounted dijalakan sekali ketika komponen sudah tampil di DOM, biasanya digunakan untuk melakukan side effect seperti mengambil data dari API, atau melakukan manipulasi DOM. 
 */
<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>