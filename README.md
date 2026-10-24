# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Reva Liyanasari  
**NIM:** 2225250101  
**Kelas:** 3A  
**Mata Kuliah:** Algoritma dan Pemrograman  
**Dosen Pengampu:** Dr. Aan Hendrayana, S.Si., M.Pd.

## 1. Tujuan

Mempelajari dan menerapkan pengolahan string menggunakan Python untuk membersihkan serta menormalisasi data nama mahasiswa dan kode kelas, menghitung jumlah kata, dan membuat inisial mahasiswa.

## 2. Struktur Folder

```text
pertemuan-10-string-2225250101/
├── README.md
├── .gitignore
├── latihan/
| └── 01_dasar_string.py
| └── 02_indeks_slicing.py
| └── 03_method_string.py
| └── 04_bersihkan_teks.py
| └── 05_split_join.py
| └── 06_pencarian_kata.py
└── tugas/
    └── normalisasi_data_mahasiswa.py
```

## 3. Cara Menjalankan Program

1. Buka folder `pertemuan-10-string-2225250101` di Visual Studio Code.
2. Pastikan Python sudah terpasang.
3. Buka terminal melalui menu **Terminal > New Terminal**.
4. Jalankan perintah berikut:

```powershell
python tugas/normalisasi_data_mahasiswa.py
```

5. Masukkan nama mahasiswa dan kode kelas ketika diminta oleh program.

## 4. Algoritma

1. Memasukkan nama lengkap mahasiswa.
2. Memasukkan kode kelas.
3. Menghapus spasi berlebih pada nama menggunakan `strip()` dan `split()`.
4. Mengubah nama menjadi format title case menggunakan `title()`.
5. Memisahkan nama menjadi beberapa kata menggunakan `split()`.
6. Mengambil huruf pertama setiap kata untuk membentuk inisial.
7. Mengubah kode kelas menjadi huruf besar menggunakan `upper()`.
8. Menggabungkan bagian kode kelas menggunakan tanda hubung dengan `join()`.
9. Menghitung jumlah kata pada nama mahasiswa.
10. Menampilkan nama bersih, kode kelas, jumlah kata, dan inisial mahasiswa.

## 5. Fungsi yang Digunakan

| Fungsi | Kegunaan |
|---|---|
| `normalisasi_nama(nama)` | Membersihkan spasi berlebih dan mengubah nama menjadi title case. |
| `buat_inisial(nama)` | Membuat inisial dari huruf pertama setiap kata nama. |
| `normalisasi_kode(kode)` | Mengubah kode kelas menjadi huruf besar dan menggunakan tanda hubung sebagai pemisah. |

## 6. Test Case

### Test Case 1

**Input:**
- Nama: `aan hendrayana`
- Kode kelas: `pmat a 2026`

**Hasil yang diharapkan:**

```text
Nama bersih : Aan Hendrayana
Kode kelas  : PMAT-A-2026
Jumlah kata : 2
Inisial     : AH
```

### Test Case 2

**Input:**
- Nama: `fATHIYYAH mUTHMAINNAH`
- Kode kelas: `kelas b`

**Hasil yang diharapkan:**

```text
Nama bersih : Fathiyyah Muthmainnah
Kode kelas  : KELAS-B
Jumlah kata : 2
Inisial     : FM
```

### Test Case 3

**Input:**
- Nama: `BUDI`
- Kode kelas: `pmtk 01`

**Hasil yang diharapkan:**

```text
Nama bersih : Budi
Kode kelas  : PMTK-01
Jumlah kata : 1
Inisial     : B
```

### Test Case 4

**Input:**
- Nama: `siti nur aisyah`
- Kode kelas: `kelas c`

**Hasil yang diharapkan:**

```text
Nama bersih : Siti Nur Aisyah
Kode kelas  : KELAS-C
Jumlah kata : 3
Inisial     : SNA
```

**Catatan:** Hasil aktual perlu diperiksa dengan menjalankan program di VS Code.

## 7. Refleksi

Pada tugas ini, saya mempelajari cara mengolah string untuk membersihkan dan menormalkan data teks. Method `strip()` digunakan untuk menghapus spasi di awal dan akhir, sedangkan `split()` membantu memisahkan teks menjadi kata-kata. Method `title()` digunakan untuk mengatur kapitalisasi nama, dan `upper()` digunakan untuk mengubah kode kelas menjadi huruf besar.

Selain itu, `join()` digunakan untuk menggabungkan kata dengan pemisah tertentu. Penggunaan fungsi membuat proses pengolahan teks lebih terstruktur dan dapat digunakan kembali. Saya juga memahami bahwa pengujian diperlukan untuk memastikan program menghasilkan keluaran sesuai dengan kebutuhan.

## 8. Sumber dan Bantuan

- Bahan Ajar Algoritma dan Pemrograman Pertemuan 10: *String dan Pengolahan Teks dalam Python*.
