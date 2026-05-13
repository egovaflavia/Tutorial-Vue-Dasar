<script setup>
import { ref } from 'vue';

const users = ref([
  { id: 1, name: "Budi", age: 20 },
  { id: 2, name: "Siti", age: 22 },
  { id: 3, name: "Andi", age: 25 }
])
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 14:56:23 
 * @Desc: Render List Object adalah proses menampilkan data dalam bentuk list yang terdiri dari objek. Dalam Vue.js, kita dapat menggunakan directive `v-for` untuk melakukan render list objek dengan mengakses properti dari setiap objek dalam array. 
 */
<template>
  <div>
    <h2>Render List Object</h2>
    <div v-for="user in users" :key="user.id" class="card">
      <h3>{{ user.name }}</h3>
      <p>Age: {{ user.age }}</p>
    </div>
  </div>
</template>