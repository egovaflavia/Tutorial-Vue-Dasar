<script setup>
  import { ref } from "vue";

  const count = ref(0)
  
  const increment = () => {
    count.value++;
  }
</script>

/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-10 12:58:12 
 * @Desc: State Ref biasanya dipakai untuk nilai tunggal (primitive) seperti string, number, boolean. State Ref digunakan untuk membuat state yang dapat berubah-ubah. State Ref menggunakan fungsi ref() untuk membuat state yang dapat berubah-ubah. State Ref juga memiliki properti value yang digunakan untuk mengakses nilai dari state tersebut. 
 */
<template>
  <div>
    <h1>Count: {{ count }}</h1>
    <button @click="increment">Increment</button> 
  </div>
</template>