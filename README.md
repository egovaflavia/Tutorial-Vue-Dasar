### Lifecycle Hook
Setiap komponen Vue memiliki beberapa lifecycle hook yang memungkinkan Anda untuk menjalankan kode pada titik-titik tertentu dalam siklus hidup komponen. Berikut adalah beberapa lifecycle hook yang umum digunakan:
1. `created()`: Dipanggil setelah instance komponen dibuat, tetapi sebelum template dirender. Cocok untuk inisialisasi data atau melakukan panggilan API.
2. `mounted()`: Dipanggil setelah template dirender dan DOM tersedia. Cocok untuk manipulasi DOM atau melakukan operasi yang memerlukan akses ke elemen DOM.
3. `updated()`: Dipanggil setelah data komponen diperbarui dan DOM dirender ulang. Cocok untuk melakukan tindakan setelah data berubah.
4. `unmounted()`: Dipanggil sebelum instance komponen dihancurkan. Cocok untuk membersihkan sumber daya atau event listener.

Dengan lifecycle hook, Anda dapat mengontrol bagaimana komponen Anda berinteraksi dengan siklus hidupnya, memungkinkan Anda untuk membuat aplikasi yang lebih dinamis dan responsif.

Import Lifecycle Hook
Untuk menggunakan lifecycle hook dalam komponen Vue, Anda dapat mengimpor fungsi-fungsi yang sesuai dari Vue. Berikut adalah contoh cara mengimpor dan menggunakan lifecycle hook dalam sebuah komponen:

```vue
<script setup>
import { onMounted, onUpdated, onUnmounted } from 'vue';
</script>
```

Lifetyle Hook Lain
onBeforeMount() - Dipanggil sebelum template dirender dan DOM tersedia.
onBeforeUpdate() - Dipanggil sebelum data komponen diperbarui dan DOM dirender ulang.
onBeforeUnmount() - Dipanggil sebelum instance komponen dihancurkan, tetapi setelah event

Diagram Lifecycle Hook
```
onBeforeMount → onMounted
       ↓
onBeforeUpdate → onUpdated
       ↓
onBeforeUnmount → onUnmounted

``` 