# ejaan-rupiah-php

Library ini adalah sebuah library yang dapat mengubah angka menjadi format terbilang. Library ini dibuat dengan bahasa pemrograman PHP dan dapat digunakan pada aplikasi yang dibangun menggunakan PHP.

## Cara Penggunaan
1. Unduh atau clone repository ini ke server Anda
2. Include file terbilang.php pada aplikasi Anda dengan menambahkan baris berikut: 
<pre>require_once "path/to/terbilang.php";</pre>
3. Panggil fungsi terbilang dengan menambahkan baris berikut:
<pre>echo terbilang(123456789);</pre>
Output yang akan muncul adalah:
<pre>Seratus Dua Puluh Tiga Juta Empat Ratus Lima Puluh Enam Ribu Tujuh Ratus Delapan Puluh Sembilan</pre>
## Keterangan
- Library ini hanya dapat mengubah angka dengan maksimal 9 digit. Angka lebih dari 9 digit akan ditolak.
- Library ini hanya dapat mengubah angka positif. Angka negatif akan ditolak.

## Kontribusi
- Jika Anda ingin berkontribusi pada library ini, Anda dapat membuat fork dari repository ini dan membuat perubahan pada bagian yang diperlukan.
- Setelah itu, silahkan buat pull request ke repository ini untuk mengajukan perubahan yang telah Anda buat.



