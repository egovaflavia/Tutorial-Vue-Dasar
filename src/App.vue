<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

 /** 
  * @Author: egovaflavia 
  * @Date: 2026-05-10 00:10:47 
  * @Desc: Props
  * Props kependekan dari Properties, yaitu sebuah mekanisme untuk mengirim data dari komponen induk ke komponen anak. Props memungkinkan kita untuk membuat komponen yang lebih fleksibel dan dapat digunakan kembali dengan memberikan nilai yang berbeda pada setiap penggunaan komponen tersebut.  
  */
<template>
  <HelloWorld name="Egova"/>
  <HelloWorld name="Riva"/>
  <HelloWorld name="Gustino"/>
</template>
