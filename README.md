## Computed Properties
Computed properties adalah nilai turunan yang dihitung berdasarkan data atau properti lain.

Keunggulan computed properties:
- Otomatis chache
- Cocok untuk logika yang kompleks

## Watcher
Watcher adalah fungsi yang dijalankan ketika data atau properti tertentu berubah.

Computed menghasilkan nilai baru
Watcher menjalankan fungsi ketika data berubah, tetapi tidak menghasilkan nilai baru.

Kapan menggunakan computed properties vs watcher?
- Gunakan computed properties untuk nilai turunan yang bergantung pada data lain.
- Gunakan watcher untuk menjalankan fungsi atau efek samping ketika data berubah.