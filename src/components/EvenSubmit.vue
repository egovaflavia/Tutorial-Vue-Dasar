<script setup>
import { ref } from 'vue'

const email = ref('')

const handleSubmit = () => {
  alert(`Email yang dimasukkan: ${email.value}`)
}
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-13 10:53:01 
 * @Desc: Event Handling - Submit Event digunakan untuk menangani event submit pada elemen HTML. Event Handling menggunakan directive v-on atau @ untuk menangani event submit. Event Handling juga dapat menggunakan method untuk menangani event submit pada elemen HTML. Event Handling digunakan untuk membuat interaksi pada aplikasi Vue.js, seperti mengirim data ke server atau memproses data yang dimasukkan oleh pengguna. 
 */
<template>
  <div>
    <h1>Event Handling - Submit Event</h1>
    <form @submit.prevent="handleSubmit">
      <!-- @submit.prevent mencegah perilaku default form submission -->
      <!-- handleSubmit akan dipanggil saat form disubmit -->
      <input v-model="email" type="email" placeholder="Masukkan email" required />
      <button type="submit">Submit</button>
    </form>
  </div>
</template>