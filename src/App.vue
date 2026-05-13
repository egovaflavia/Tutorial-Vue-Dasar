<script setup>
import HelloWorld from './components/HelloWorld.vue'
import OnMounted from './components/OnMounted.vue'
import OnUpdated from './components/OnUpdated.vue'
import OnUnmounted from './components/OnUnmounted.vue'  
</script>

<template>
  <!-- <HelloWorld /> -->
  <OnMounted />
  <OnUpdated />
  <OnUnmounted />
</template>
