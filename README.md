Nama: Binar Nur Alimin
NIM: 2205101093
Kelas: TIF-5D
# Latihan Praktikum Semantic HTML

---

## 1. Analisis Kode HTML

### Masalah yang Ditemukan:
1. **Struktur Dasar HTML Tidak Lengkap**: Kode awal tidak menyertakan tag `<html>`, `<head>`, dan `<body>`, yang merupakan elemen penting untuk struktur HTML.
2. **Penggunaan Tag `<header>` di Luar `<body>`**: Tag `<header>` ditempatkan langsung setelah `<!DOCTYPE html>`, padahal seharusnya berada di dalam tag `<body>`.
3. **Penempatan Konten yang Tidak Berurutan**: Struktur kode tidak rapi dan beberapa elemen diletakkan di luar konteks yang sesuai.

### Perbaikan yang Dilakukan:
1. **Struktur HTML yang Lengkap**: Menambahkan tag `<html>`, `<head>`, dan `<body>` untuk memberikan kerangka dasar HTML yang benar.
2. **Lokasi yang Benar untuk `<header>`, `<nav>`, `<section>`, dan `<footer>`**: Semua elemen semantik ditempatkan di dalam `<body>`, sesuai dengan standar HTML5.
3. **Penambahan Metadata**: Menambahkan `<meta charset="UTF-8">` dan `<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk mendukung tampilan yang optimal pada berbagai perangkat.
4. **Menambahkan Tag `<title>`**: Tag `<title>` ditambahkan pada bagian `<head>`, yang penting untuk SEO dan identifikasi halaman.

---

## 2. Analisis Kode CSS

### Masalah yang Ditemukan:
1. **Kesalahan Penulisan Kurung pada Selector `section`**: Pada selector `section`, terdapat kesalahan dalam penggunaan kurung. Seharusnya kurung `{` digunakan sebagai pembuka.
2. **Kekurangan Penutupan Kurung Kurawal pada CSS**: Pada selector `header`, `nav`, `section`, dan `footer`, terdapat kesalahan karena tidak menutup deklarasi dengan kurung kurawal `}`.

### Perbaikan yang Dilakukan:
1. **Penulisan Kurung yang Benar pada CSS**: Memastikan bahwa setiap selector membuka dengan `{` dan menutup dengan `}` sesuai sintaks CSS yang benar.
2. **Perbaikan Properti Layout**: Dengan perbaikan ini, `grid-area` akan mengatur layout halaman dengan benar, setiap elemen akan memiliki padding yang sama, dan tampilan layout akan rapi sesuai desain grid pada bagian `<body>`.

---

