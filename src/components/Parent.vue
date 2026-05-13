<script setup>
import { ref, onMounted } from "vue"
import Child from "./Child.vue"

const childRef = ref(null)

onMounted(() => {
  childRef.value.sayHello()
})
</script>

<template>
  <Child ref="childRef" />
</template>
