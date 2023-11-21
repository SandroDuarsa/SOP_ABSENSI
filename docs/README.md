## <h1>1.  Konfigurasi </h1>
Konfigurasi harus dilakukan secara berurutan dalam urutan sebagai berikut:

### 1. Konfigurasi Server:
- Tentukan dan atur konfigurasi server yang diperlukan untuk mendukung aplikasi termasuk rencana pencadangan data.

### 2. Konfigurasi Dashboard:
1. Konfigurasi Master Data (Add Data Pegawai)
   <p>1.1. Masuk ke workspace Absensi.</p>
   <p>2.2. Pilih employee data.</p>
   <p>3.3. Tambahkan data.</p>

2. Konfigurasi License
    Masuk ke doctype FR License.
	<h5>(Tab License)</h5>
   <p>2.1. Tentukan client name kemudian input.</p>
	<h5>(Tab App Config)</h5>
   <p>2.2. Pilih app mode public.</p>
   <p>2.3. Enable Allow Register, Allow Check in.</p>
   <p>2.4. Isi network interval dengan 20.</p>
   <p>2.5. Isi screen distance dengan 55 dan check in timer dengan 1.</p>
   <p>2.6. Isi URL Link, Person Data Source URL, Custom Face Recognition URL, Custom Face Register URL dengan link yang sudah diberikan tim dev.</p>
    <h5>(Tab App Theme)</h5>
   <p>2.7. Isi Button Primary Color, Button Secondary Color, Text Primary Color, Text Secondary Color.</p>
   <p>2.8. Upload Background Image dan Logo.</p>
   <p>2.9. Simpan.</p>

### 3. Konfigurasi Aplikasi Mobile:
   1. Masukkan nama organisasi sesuai dengan nama client.
   2. Masukkan license code dari FR License.
   3. Salin Device Id.
   4. Buka Dashboard, pergi ke FR License, lalu pilih license yang dimasukkan di mobile app.
   5. Pada Tab License di bagian device, tambahkan row.
   6. Masukkan Device id dan isi device name dengan format MERK_JENIS(HP/TABLET)_LETAK.
   7. Simpan.

## <h1>2. Pengujian</h1>
### a. Uji Kinerja
- Lakukan pengujian kinerja pada perangkat yang diimplementasikan yang harus diuji:
  1. Kestabilan Jaringan di lokasi yang diimplementasikan.
  2. Pencarian Member di Register pada mobile apps.
  3. Register Wajah pada mobile apps.
  4. Absensi pada mobile apps.
  </br>
  <i style="color: red;">*Pengujian mencakup Bisa/tidaknya perangkat membuka/mengeksekusi fitur tersebut, waktu upload (add dokumen hasil pengujian).</i>

## <h1>3. Implementasi</h1>
### a. Penjadwalan Pelatihan
- Tentukan jadwal pelatihan yang disepakati oleh kedua belah pihak.

### b. Pelatihan Pengguna:
- Untuk pelatihan: 1x tatap muka dan diberikan dokumentasi penggunaan aplikasi yang dapat digunakan oleh customer untuk mempelajari aplikasi secara mandiri.
  #### Alur Pelatihan tatap muka:
  1. Berikan pelatihan kepada PIC yang ditunjuk customer sesuai dengan kapasitasnya untuk memastikan pemahaman yang baik tentang penggunaan aplikasi.
  2. Berikan materi pelatihan yang mencakup fitur-fitur esensial, penanganan masalah yang umumnya terjadi, dan cara terbaik penggunaan aplikasi.
  Materi Bisa Diakses di : [Link Materi Pelatihan](https://docs-facerecognition.vercel.app/)
  3. Berikan Dokumentasi aplikasi yang bisa diakses sebagai sumber referensi.
  Dokumentasi bisa diakses di : [Link Dokumentasi Aplikasi](https://docs-facerecognition.vercel.app/)

#

## <h1>4. Mitigasi</h1>
Mitigasi penting karena tim bisa dengan cepat mengidentifikasi dan mengurangi dampak negatif dalam proyek. Dengan mitigasi, tim dapat proaktif mengatasi risiko untuk memastikan kelancaran proyek.

### a. Komunikasi:
- Pastikan tim berkomunikasi secara efektif dengan klien untuk memitigasi potensi masalah.</br>
  <i>Dengan cara membuat group chat (anggota: owner, PIC, tim dev, implementator)</i>

## <h1>5. Evaluasi</h1>
(penjelasan mengapa step ini penting dan tidak boleh diskip)
### a. Pemantauan:
- Lakukan pemantauan secara berkala untuk menilai kemajuan proyek dan mengidentifikasi perubahan yang mungkin diperlukan setiap 1 minggu sekali untuk 1 bulan pertama.
- Lakukan pemantauan secara berkala setiap 2 minggu untuk bulan 2 - 3.
- Lakukan pemantauan secara berkala setiap bulan untuk bulan 4 dan seterusnya.
