<script setup>
defineProps({
  name: String,
})  
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-10 00:15:01 
 * @Desc: Pada contoh di atas, kita mendefinisikan sebuah komponen HelloWorld yang menerima sebuah prop bernama name. Kemudian, kita menggunakan prop tersebut untuk menampilkan pesan "Hello, {name}" di dalam template. Dengan menggunakan props, kita dapat membuat komponen yang lebih dinamis dan dapat digunakan kembali dengan memberikan nilai yang berbeda pada setiap penggunaan komponen tersebut.
 */
<template>
  <h2>Hello, {{ name }}</h2>
</template>