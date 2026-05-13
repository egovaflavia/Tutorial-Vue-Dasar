## Form Binding
### v-model ?
`v-model` adalah directive yang digunakan untuk membuat two-way data binding. Artinya, data yang diikat dengan `v-model` akan secara otomatis diperbarui ketika pengguna mengubah nilai input, dan sebaliknya, jika data diubah dalam JavaScript, nilai input juga akan diperbarui.

### Modifier pada v-model
```html
<input v-model.lazy="name" />
<input v-model.trim="name" />
<input v-model.number="age" />
```