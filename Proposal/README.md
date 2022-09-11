# Proposal
## Permasalahan
Masih adanya sistem absensi  manual di perusahaan yang kurang terstruktur, jadi bagaimana cara menampilkan dan membuat laporan dari sistem absensi karyawan sehingga lebih terstruktur dan mudah dimonitor.

## Rancangan solusi
-	Menganalisa alur kerja pada proses input absensi pegawai pada CV.Karisma , dengan melakukan proses wawancara dengan pihak Personalia.
-	Menyediakan fitur yang dapat menampilkan dan membuat laporan dari sistem absensi karyawan sehingga lebih terstruktur dan mudah di monitor pada aplikasi mobile, sehingga karyawan dapat dengan mudah melihat dan mengevaluasi kembali kinerjanya.

## Use Case
-	Use admin memungkinkan aktor untuk dapat mengakses atau mengelola data karyawan, mengelola data divisi, mengelola setting jan absen dan laporan rekap absensi.
-	Use karyawan dapat melihat datayang ada pada akses karyawan untuk dapat mengakses profil karyawan, melakukan absensi dan melihat absensi.

## Struktur data
### User 
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|Integer|255|
|nik|integer|14772|
|nama|string|Septi|
|telp|integer|255
|email|string|Septi25@gmail.com|
|username|string|lutfiah|
|password|string|fiah|

### Absensi
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|255
|tanggal|date|11-09-2022|
|waktu|time|13:30:12|
|keterangan|string|hadir|

### Divisi 
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|255
|nama|string|personalia|

### Jam
|Atribut|Tipe Data|Contoh|
|--|--|--|
|id|integer|255
|start|datetime|11-09-2022/13:30:12|
|finish|datetime|11-09-2022/20:00:00|

## UX Wireframe
![WhatsApp Image 2022-09-11 at 23 09 37](https://user-images.githubusercontent.com/112858041/189541581-fdd36d7a-0049-4d2a-bef8-2ae77deff97b.jpeg)
