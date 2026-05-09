<script setup>
defineProps({
  title: String,
  description: String
})
</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-10 00:18:52 
 * @Desc: Pada contoh di atas, kita mendefinisikan sebuah komponen Card yang menerima dua prop, yaitu title dan description. Kemudian, kita menggunakan kedua prop tersebut untuk menampilkan judul dan deskripsi di dalam template. Dengan menggunakan props, kita dapat membuat komponen yang lebih fleksibel dan dapat digunakan kembali dengan memberikan nilai yang berbeda pada setiap penggunaan komponen tersebut. 
 */
<template>
  <div class="card">
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
  </div>  
</template>