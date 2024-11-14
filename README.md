# SEMANTIC-HTML

Latihan Praktikum Semantic HTML

### Latihan 1 : Semantic HTML

### Menganalisis kode HTML & CSS 

### ANALISIS KODE  HTML :

1. Struktur Dasar HTML yang Tidak Lengkap: Kode ini tidak memiliki elemen <html> dan <body>. Semua dokumen HTML perlu dibungkus dalam tag <html> dan bagian kontennya perlu berada dalam <body>. Selain itu, tag <head> yang     berisi metadata seperti judul halaman, pengaturan karakter, dan referensi CSS juga tidak ada.

2. Penggunaan Tag <header> di Luar <body>: Tag <header> tidak boleh ditempatkan langsung setelah <!DOCTYPE html>. Seharusnya berada di dalam <body>.

3. Penempatan Konten yang Tidak Berurutan: Kode ini memiliki struktur yang kurang baik, dengan tag yang ditempatkan di luar konteks yang sesuai.

### Perbedaan Setelah Diperbaiki :
   
1. Struktur yang Lengkap: Kode yang telah diperbaiki memiliki tag <html>, <head>, dan <body>, yang memberikan struktur dasar HTML yang lengkap.

2. Lokasi yang Benar untuk <header>, <nav>, <section>, dan <footer>: Setiap tag elemen semantik sekarang berada dalam <body>, sesuai standar HTML5.

3. Penambahan Metadata: Tag <meta charset="UTF-8"> dan <meta name="viewport"> ditambahkan untuk memastikan tampilan halaman yang optimal di perangkat apa pun.

4. Penambahan <title>: Menambahkan tag <title> pada bagian <head>, yang penting untuk SEO dan identifikasi halaman.

5. Peningkatan Keterbacaan Konten: Bagian <section> diperjelas dengan menambahkan elemen <h2> untuk judul dan <p> untuk isi konten.

### ANALISIS KODE  CSS :

1. Kesalahan Penulisan Kurung pada Selector section
   Pada selector section, terdapat kesalahan penulisan tanda kurung. Kurung pembuka ( seharusnya ditulis dengan { agar sesuai dengan sintaks CSS yang benar.
   css Salin kode.

2. Kekurangan pada Penutupan Properti CSS
   Pada selector header, nav, section, footer, kode CSS tidak ditutup dengan kurung kurawal }. Hal ini menyebabkan properti padding: 5px; mungkin tidak terbaca dengan benar atau dapat menyebabkan kesalahan dalam penataan     elemen-elemen yang ada.

3. Setelah Diperbaiki
   Setelah perbaikan dilakukan, kode akan lebih rapi dan dapat berfungsi dengan benar sesuai harapan. grid-area akan mengatur layout halaman dengan benar, dan setiap elemen akan memiliki padding yang sama sehingga tampil     lebih rapi.
   Dengan struktur yang benar, section akan di-render dengan background sesuai warna yang telah ditentukan, dan tampilan layout secara keseluruhan akan sesuai dengan desain grid yang ditentukan di bagian body.
