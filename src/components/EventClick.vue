<script setup>
import { ref } from 'vue'

const count = ref(0)

const increment = () => {
  count.value++
}
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 10:50:28 
 * @Desc: Event Handling - Click Event digunakan untuk menangani event click pada elemen HTML. Event Handling menggunakan directive v-on atau @ untuk menangani event click. Event Handling juga dapat menggunakan method untuk menangani event click pada elemen HTML. Event Handling digunakan untuk membuat interaksi pada aplikasi Vue.js.
 */
<template>
  <div>
    <h1>Event Handling</h1>
    <p>Count: {{ count }}</p>
    <button @click="increment">Increment</button>
  </div>
</template>