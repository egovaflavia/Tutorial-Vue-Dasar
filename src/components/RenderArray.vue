<script setup>
import { ref } from 'vue'

const fruits = ref(['Apple', 'Banana', 'Cherry'])
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 14:45:15 
 * @Desc: List Rendering adalah proses menampilkan data dalam bentuk list atau daftar. Dalam Vue.js, kita dapat menggunakan directive `v-for` untuk melakukan list rendering.
 */
<template>
  <div>
    <h2>Render Array</h2>
    <ul>
      <li v-for="fruit in fruits" :key="fruit">
        <!-- v-for="fruit in fruits" melakukan loop terhadap array fruits -->
        <!-- :key="fruit" setiap item harus memiliki key unik -->
        {{ fruit }}
      </li>
    </ul>
  </div>
</template>