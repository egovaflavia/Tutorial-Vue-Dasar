<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Card from './components/Card.vue'
import PropsValidasi from './components/PropsValidasi.vue'
</script>

 /** 
  * @Author: egovaflavia 
  * @Date: 2026-05-10 00:10:47 
  * @Desc: Props
  * Props kependekan dari Properties, yaitu sebuah mekanisme untuk mengirim data dari komponen induk ke komponen anak. Props memungkinkan kita untuk membuat komponen yang lebih fleksibel dan dapat digunakan kembali dengan memberikan nilai yang berbeda pada setiap penggunaan komponen tersebut.  
  */
<template>
  <Card title="Card Title" description="This is a description of the card." />
  <HelloWorld name="Egova" />
  <HelloWorld name="Flavia" />
  <PropsValidasi :age="25" />
</template>
