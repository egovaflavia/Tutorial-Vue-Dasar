<script setup>
import{ ref } from 'vue'

const count = ref(0)
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 10:51:08 
 * @Desc: Event Handling - Click Inline Expression digunakan untuk menangani event click pada elemen HTML dengan menggunakan inline expression. Event Handling menggunakan directive v-on atau @ untuk menangani event click. Event Handling juga dapat menggunakan method untuk menangani event click pada elemen HTML. 
 */
<template>
  <div>
    <h1>Event Handling</h1>
    <p>Count: {{ count }}</p>
    <button @click="count++">Increment</button>
  </div>
</template>