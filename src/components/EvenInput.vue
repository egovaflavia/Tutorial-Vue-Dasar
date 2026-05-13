<script setup>
import { ref } from 'vue'
const name = ref('')
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 10:49:56 
 * @Desc: Event Handling - Input Event digunakan untuk menangani event input pada elemen HTML. Event Handling menggunakan directive v-on atau @ untuk menangani event input. Event Handling juga dapat menggunakan method untuk menangani event input pada elemen HTML. 
 */
<template>
  <div>
    <input v-model="name" placeholder="Ketik Nama" />
    <p>Hello {{ name }}</p>
  </div>
</template>

