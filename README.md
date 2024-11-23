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
Berikut penjelasan rinci tetapi singkat untuk kode program:

1. **Data Mahasiswa**:
   - Data disimpan dalam sebuah *dictionary*, di mana nama mahasiswa adalah **kunci**, dan nilai-nilainya adalah **nilai sub-dictionary**.

2. **Fungsi Utama**:
   - **`tambah_data()`**: Meminta input nama, nilai tugas, UTS, UAS, lalu menghitung nilai akhir menggunakan formula:
     \[
     \text{Nilai Akhir} = (\text{Tugas} \times 0.3) + (\text{UTS} \times 0.35) + (\text{UAS} \times 0.35)
     \]
     Data disimpan dalam *dictionary*.
   - **`ubah_data()`**: Mengedit data mahasiswa yang ada berdasarkan nama. Jika nama tidak ditemukan, memberikan pesan error.
   - **`hapus_data()`**: Menghapus data mahasiswa berdasarkan nama. Jika nama tidak ditemukan, memberikan pesan error.
   - **`tampilkan_data()`**: Menampilkan semua data mahasiswa dalam format tabel rapi dengan kolom nama, tugas, UTS, UAS, dan nilai akhir.
   - **`cari_data()`**: Menampilkan detail data mahasiswa tertentu berdasarkan nama.

3. **Menu Interaktif**:
   - Fungsi **`menu()`** menyediakan opsi untuk pengguna, seperti menambah, mengubah, menghapus, menampilkan, atau mencari data. Pengguna juga dapat keluar dari program.

4. **Rapi dan Informatif**:
   - Tabel menggunakan format *string formatting* untuk memastikan data terlihat rapi dan mudah dibaca.


