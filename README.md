### Template Refs
Secara defaul Vue bekerja dengan data binding (state -> ui), Namun kadang kita membutuhkan akses langsung ke element DOM, Misalnya :
  - Untuk memfokuskan input ketika halaman dimuat
  - Untuk mengakses nilai dari input yang tidak menggunakan v-model
  - Untuk memanggil method pada child component

### Kapan Menggunakan Template Refs ?
  - Ketika kita membutuhkan akses langsung ke element DOM
  - Ketika kita membutuhkan akses langsung ke child component
  - Ketika kita membutuhkan parent memanggil method pada child component