<script setup>
const props = defineProps({
  defineProps<{
    label?: string
  }>(),{
    label: 'Tombol Default'
  }
})
</script>

<template>  
  <button>{{ props.label }}</button>
</template>