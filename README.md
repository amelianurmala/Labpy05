# Labpy05
## TUGAS PRATIKUM - Pertemuan ke 10

Nama   : Amelia Nurmala Dewi

NIM    : 312410199

Kelas  : TI.24.A2

# Berikut ini adalah Kodenya

![Screenshot (126)](https://github.com/user-attachments/assets/3c2a3458-2c5e-41f6-8f20-7d93372944d9)
![Screenshot (127)](https://github.com/user-attachments/assets/cc566767-4ec6-4843-8327-7862a4ce9795)
![Screenshot (128)](https://github.com/user-attachments/assets/9c31812e-a946-4b95-a1bc-c9e9d97200ff)

# Berikut adalah Penjelasannya

### 1. **Struktur Program**
Program ini merupakan aplikasi pengelolaan data nilai mahasiswa menggunakan *dictionary*. Program memiliki fitur untuk menambah, mengubah, menghapus, menampilkan, dan mencari data mahasiswa.

---

### 2. **Komponen Program**

#### a. **Variabel Global**
```python
data_mahasiswa = {}
```
Variabel `data_mahasiswa` adalah *dictionary* kosong yang digunakan untuk menyimpan data setiap mahasiswa. Setiap mahasiswa akan disimpan dalam bentuk pasangan kunci-nilai (`key-value`), di mana:
- **Kunci**: Nama mahasiswa (string).
- **Nilai**: Sub-*dictionary* yang berisi nilai tugas, UTS, UAS, dan nilai akhir.

---

#### b. **Fungsi `tambah_data()`**
Fungsi ini digunakan untuk menambahkan data mahasiswa baru. Langkah-langkahnya:
1. Meminta pengguna memasukkan nama mahasiswa, nilai tugas, UTS, dan UAS.
2. Menghitung nilai akhir menggunakan rumus:
   \[
   \text{Nilai Akhir} = (\text{Tugas} \times 0.3) + (\text{UTS} \times 0.35) + (\text{UAS} \times 0.35)
   \]
3. Menambahkan data ke dalam *dictionary* `data_mahasiswa` dengan nama mahasiswa sebagai kunci.
4. Menampilkan pesan bahwa data berhasil ditambahkan.

---

#### c. **Fungsi `ubah_data()`**
Fungsi ini digunakan untuk mengubah data mahasiswa yang sudah ada. Langkah-langkahnya:
1. Meminta nama mahasiswa yang ingin diubah.
2. Mengecek apakah nama tersebut ada di dalam `data_mahasiswa`.
   - Jika ditemukan, meminta nilai tugas, UTS, dan UAS baru, menghitung ulang nilai akhir, lalu memperbarui data di *dictionary*.
   - Jika tidak ditemukan, menampilkan pesan bahwa mahasiswa tidak ditemukan.

---

#### d. **Fungsi `hapus_data()`**
Fungsi ini digunakan untuk menghapus data mahasiswa. Langkah-langkahnya:
1. Meminta nama mahasiswa yang ingin dihapus.
2. Mengecek apakah nama tersebut ada di dalam `data_mahasiswa`.
   - Jika ditemukan, menghapus data menggunakan perintah `del`.
   - Jika tidak ditemukan, menampilkan pesan bahwa mahasiswa tidak ditemukan.

---

#### e. **Fungsi `tampilkan_data()`**
Fungsi ini digunakan untuk menampilkan semua data mahasiswa yang sudah tersimpan. Langkah-langkahnya:
1. Mengecek apakah ada data di dalam `data_mahasiswa`.
   - Jika ada, menampilkan data dalam bentuk tabel dengan format:
     ```
     Nama              Tugas   UTS     UAS     Nilai Akhir
     ------------------------------------------------------
     Nama_Mahasiswa    90.00   85.00   88.00   87.15
     ```
   - Jika tidak ada, menampilkan pesan bahwa belum ada data mahasiswa.
2. Data ditampilkan menggunakan perulangan `for` untuk setiap item di *dictionary* `data_mahasiswa`.

---

#### f. **Fungsi `cari_data()`**
Fungsi ini digunakan untuk mencari data mahasiswa berdasarkan nama. Langkah-langkahnya:
1. Meminta nama mahasiswa yang ingin dicari.
2. Mengecek apakah nama tersebut ada di dalam `data_mahasiswa`.
   - Jika ditemukan, menampilkan nilai tugas, UTS, UAS, dan nilai akhir mahasiswa tersebut.
   - Jika tidak ditemukan, menampilkan pesan bahwa mahasiswa tidak ditemukan.

---

#### g. **Fungsi `menu()`**
Fungsi utama yang menampilkan menu interaktif untuk pengguna. Langkah-langkahnya:
1. Menampilkan daftar menu:
   - Tambah Data
   - Ubah Data
   - Hapus Data
   - Tampilkan Data
   - Cari Data
   - Keluar
2. Meminta pengguna memilih salah satu opsi.
3. Menjalankan fungsi sesuai dengan pilihan pengguna:
   - `1`: Menjalankan fungsi `tambah_data()`.
   - `2`: Menjalankan fungsi `ubah_data()`.
   - `3`: Menjalankan fungsi `hapus_data()`.
   - `4`: Menjalankan fungsi `tampilkan_data()`.
   - `5`: Menjalankan fungsi `cari_data()`.
   - `6`: Keluar dari program.
4. Jika pilihan tidak valid, menampilkan pesan error.

---

### 3. **Keunggulan Program**
1. **Organisasi Struktur Data**:
   Data disimpan dalam bentuk *dictionary* yang efisien untuk pencarian dan pengelolaan.
2. **Interaktif**:
   Program berjalan dalam bentuk menu yang mudah digunakan.
3. **Komputasi Nilai Akhir**:
   Program secara otomatis menghitung nilai akhir berdasarkan bobot nilai tugas, UTS, dan UAS.
4. **Kemudahan Pengelolaan**:
   Pengguna dapat menambah, mengubah, menghapus, menampilkan, dan mencari data dengan mudah.

---


# Berikut adalah hasilnya (Output)


1. Tambahkan Data
   
   ![Screenshot (129)](https://github.com/user-attachments/assets/53b4ffd5-efeb-4c34-bd8b-835dded66e3c)
   

2. Tampilkan Data
   
   ![Screenshot (130)](https://github.com/user-attachments/assets/4e50d3d9-3f4b-49f6-95db-63aad3d04a22)
   

3. Ubah Data
   
   ![Screenshot (131)](https://github.com/user-attachments/assets/d22c6a5f-8538-4426-9522-ea3758ddb4f4)
   

4. Cari Data
   
   ![Screenshot (132)](https://github.com/user-attachments/assets/ef3e0dfc-8062-4609-9ab9-e23f616a6495)
   

5. Hapus Data
   
   ![Screenshot (133)](https://github.com/user-attachments/assets/d7d5382b-21ac-442b-86fa-4829a327f30d)
   

6. Keluar
    
   ![Screenshot (137)](https://github.com/user-attachments/assets/0ecc686c-295e-4a16-b85c-650a47bad10f)








