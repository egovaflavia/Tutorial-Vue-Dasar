<script setup>
import { ref } from 'vue'

const person = ref({
  name: 'John Doe',
  age: 30,
  email: 'john.doe@example.com'
})
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 14:49:09 
 * @Desc: Render Object adalah proses menampilkan data dalam bentuk objek. Dalam Vue.js, kita dapat menggunakan directive `v-for` untuk melakukan render objek dengan mengakses key dan value dari objek tersebut. 
 */
<template>
  <div>
    <h2>Render Object</h2>
    <ul>
      <li v-for="(value, key) in person" :key="key">
        {{ key }}: {{ value }}
      </li>
    </ul>
  </div>
</template>