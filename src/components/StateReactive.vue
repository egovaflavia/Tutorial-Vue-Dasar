<script setup>
import { reactive } from "vue";

const user = reactive({
  name: "Egovaflavia",
  age: 25
})

const tambahUmur = () => {
  user.age++;
}

</script>
/** 
 * @Author: egovaflavia 
 * @Date: 2026-05-10 13:01:22 
 * @Desc: State Reactive dipakai untuk object atau array. Digunakan untuk membuat state yang dapat berubah-ubah. State Reactive menggunakan fungsi reactive() untuk membuat state yang dapat berubah-ubah. State Reactive juga memiliki properti yang digunakan untuk mengakses nilai dari state tersebut. 
 */
<template>
  <div>
    <p>Name: {{ user.name }}</p>
    <p>Age: {{ user.age }}</p>
    <button @click="tambahUmur">Tambah Umur</button>
  </div>
</template>