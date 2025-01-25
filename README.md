# Aplikasi Cek Cuaca Sederhana

Aplikasi desktop berbasis Java Swing untuk mengecek kondisi cuaca secara real-time menggunakan **OpenWeatherMap API**. Aplikasi ini memungkinkan pengguna untuk melihat cuaca terkini berdasarkan kota, menyimpan data cuaca ke file, dan mengelola daftar kota favorit.

---

## Fitur

1. **Cek Cuaca**
   - Pengguna dapat memasukkan nama kota untuk melihat kondisi cuaca terkini, termasuk suhu, deskripsi cuaca, dan kelembapan.

2. **Simpan ke Daftar Favorit**
   - Kota yang sering dicari dapat ditambahkan ke daftar favorit dan dipilih dengan cepat.

3. **Tampilkan Gambar Cuaca**
   - Aplikasi menampilkan ikon cuaca berdasarkan data yang didapat dari API.

4. **Ekspor Data**
   - Data cuaca yang telah ditampilkan dapat diekspor ke file `.csv`.

5. **Impor Data**
   - Data cuaca dari file `.csv` dapat dimuat kembali ke tabel dalam aplikasi.

6. **Hapus Data**
   - Pengguna dapat menghapus baris tertentu dari tabel.

7. **Keluar Aplikasi**
   - Tombol untuk keluar dari aplikasi.

## Prasyarat

- **Java Development Kit (JDK)** versi 8 atau lebih baru.
- Koneksi internet aktif untuk mengakses API cuaca.
- API Key dari [OpenWeatherMap](https://openweathermap.org/) (dapat diatur dalam kode).


2. **Kompilasi dan Jalankan Aplikasi**
- Buka terminal atau IDE (misalnya NetBeans atau IntelliJ IDEA).
- Kompilasi proyek dengan perintah:
  ```
  javac apkCekCuacaSederhana.java
  ```
- Jalankan aplikasi:
  ```
  java apkCekCuacaSederhana
  ```

3. **Masukkan API Key**
- Pastikan mengganti variabel `apiKey` di dalam kode dengan API key Anda yang valid:
  ```java
  private String apiKey = "API_KEY_ANDA";
  ```

4. **Gunakan Aplikasi**
- Masukkan nama kota di kolom input, lalu klik tombol **Cek Cuaca**.
- Tambahkan kota favorit, ekspor data, atau impor data sesuai kebutuhan.

## Struktur UI

- **Input Kota**: Kolom input untuk memasukkan nama kota.
- **Tabel Cuaca**: Menampilkan data cuaca berupa:
- Tanggal
- Kota
- Suhu
- Deskripsi Cuaca
- Kelembapan
- **Ikon Cuaca**: Menampilkan gambar kondisi cuaca berdasarkan data API.
- **Tombol Fungsional**:
- **Cek Cuaca**
- **Simpan ke Favorite**
- **Ekspor**
- **Impor**
- **Hapus**
- **Keluar**

## Dependensi

- **JSON Parsing**: Menggunakan library bawaan `org.json` untuk memproses data dari API.
- **Networking**: Menggunakan `HttpURLConnection` untuk mengambil data cuaca.

---

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo

![App Screenshot](https://github.com/AhmadDzulFauzilAzhim/apkCekCuacaSederhana/blob/main/img/demo%20aplikasi%20cek%20cuaca%20sederhana.gif)
