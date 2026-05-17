<script setup>
import { reactive, watch } from "vue"

const user = reactive({
  name: "Budi",
  address: { city: "Jakarta" }
})

watch(
  () => user.address,
  (newVal) => {
    console.log("Alamat berubah:", newVal)
  },
  { deep: true, immediate: true }
)
</script>
