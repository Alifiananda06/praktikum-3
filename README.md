# praktikum-3

## SQL Constraint

. SQL Constraint digunakan untuk menentukan aturan untuk data dalam tabel.

. Constraint digunakan untuk membatasi jenis data yang bisa masuk ke tabel. Ini memastikan keakuratan dan keandalan data dalam tabel.

. Constraint dapat berupa level kolom atau level tabel.

. Constraint level kolom berlaku untuk kolom, dan batasan level tabel berlaku untuk seluruh tabel.

## Tugas Praktikum

. Implementasikan penggunaan CONSTRAINT FOREIGN KEY pada semua tabel yang berelasi.

. yang perlu diperhatikan:

> tipe data pada field yang berelasi harus sama termasuk juga ukuran datanya.
> misal: pada tabel dosen, kd_ds VARCHAR(10) maka tabel yang merujuk yaitu tabel mahasiswa, kd_ds juga harus bertipe VARCHAR(10).

. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen.

. Hapus satu record data pada tabel dosen yang telah dirujuk pada tabel mahasiswa.

. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT

. Lakukan perubahan data pada tabel dosen (kd_ds)

. Lakukan penghapusan data pada tabel dosen

. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL

. Lakukan penghapusan data pada tabel dosen

## Evaluasi dan Pertanyaan

. Tulis semua perintah-perintah SQL percobaan di atas beserta outputnya! 

. Apa bedanya penggunaan RESTRICT dan penggunaan CASCADE?

>Restrict = yaitu perubahan data dan penghapusan data tidak diijinkan pada tabel referensi (parent table) apabila pada tabel child sudah ada yang merujuk pada data tersebut. Cascade = yaitu perubahan atau penghapusan data pada tabel referensi (parent table) akan diikuti oleh tabel child

. Berikan kesimpulan anda!

> Dalam kesimpulannya, RESTRICT dan CASCADE digunakan untuk mengatur perilaku ketika ada perubahan atau penghapusan data pada tabel utama. Jika digunakan dengan benar, ini dapat membantu memastikan integritas referensial dan konsistensi data antara tabel-tabel yang saling berhubungan.
