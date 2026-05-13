<script setup>
import { ref } from 'vue'

const fruits = ref(['Apple', 'Banana', 'Cherry'])
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 14:49:14 
 * @Desc: Render Array with Index adalah proses menampilkan data dalam bentuk array dengan menampilkan index atau posisi dari setiap item dalam array tersebut. Dalam Vue.js, kita dapat menggunakan directive `v-for` untuk melakukan render array dengan index dengan mengakses index dan value dari array tersebut. 
 */
<template>
  <div>
    <h2>Render Array with Index</h2>
    <ul>
      <li v-for="(fruit, index) in fruits" :key="index">
        {{ index }} - {{ fruit }}
      </li>
    </ul>
  </div>
</template>