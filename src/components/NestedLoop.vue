<script setup>
import { ref } from 'vue'
const categories = ref([
  { name: "Buah", items: ["Apel", "Mangga", "Jeruk"] },
  { name: "Sayur", items: ["Bayam", "Wortel", "Tomat"] }
])
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 14:56:16 
 * @Desc: Nested Loop adalah proses melakukan loop di dalam loop lainnya. Dalam Vue.js, kita dapat menggunakan directive `v-for` secara bersarang untuk melakukan nested loop. Contohnya, kita dapat memiliki sebuah array yang berisi objek, dan setiap objek tersebut memiliki array lain yang ingin kita render. Dengan menggunakan nested loop, kita dapat menampilkan data tersebut dengan mudah. 
 */
<template>
  <div>
    <h2>Nested Loop</h2>
    <div v-for="category in categories" :key="category.name">
      <h3>{{ category.name }}</h3>
      <ul>
        <li v-for="item in category.items" :key="item">{{ item }}</li>
      </ul>
    </div>
  </div>
</template>