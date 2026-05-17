<script setup>
import { ref, watch } from "vue"

const firstName = ref("Budi")
const lastName = ref("Santoso")

watch([firstName, lastName], ([newFirst, newLast]) => {
  console.log("Nama baru:", newFirst, newLast)
})
</script>
