# labpy08

Nama : Ahmad Ibnu Abdillah

NIM : 312410489

TI.24.A.5

# Kode Program

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/9e72bc14c4ba0e4c3070bc981b008e75d1c41c7f/Screenshot%202024-12-10%20204122.png)
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/9e72bc14c4ba0e4c3070bc981b008e75d1c41c7f/Screenshot%202024-12-10%20204134.png)

# Penjelasan Kode

### 1. **Kelas `Student`**
   - **Tujuan**: Mewakili objek mahasiswa dengan atribut-atribut:
     - `nim`: Nomor Induk Mahasiswa
     - `nama`: Nama mahasiswa
     - `tugas`: Nilai tugas
     - `uts`: Nilai Ujian Tengah Semester
     - `uas`: Nilai Ujian Akhir Semester
     - `akhir`: Nilai akhir yang dihitung secara otomatis.
   - **Metode `calculate_final_grade`**: Menghitung nilai akhir berdasarkan formula:
     \[
     \text{nilai akhir} = 0.3 \times \text{tugas} + 0.35 \times \text{uts} + 0.35 \times \text{uas}
     \]

### 2. **Fungsi `display_menu`**
   - Menampilkan menu pilihan utama kepada pengguna.

### 3. **Fungsi `display_students`**
   - **Tujuan**: Menampilkan daftar mahasiswa dalam format tabel yang rapi.
   - Jika tidak ada data mahasiswa, tabel akan menunjukkan pesan "TIDAK ADA DATA".

### 4. **Fungsi `find_student_index`**
   - **Tujuan**: Mencari indeks mahasiswa berdasarkan nama.
   - Jika mahasiswa ditemukan, mengembalikan indeks; jika tidak, mengembalikan `None`.

### 5. **Fungsi `main`**
   - Fungsi utama yang berisi loop untuk menerima input dari pengguna. Fitur-fiturnya meliputi:
     - **Tambah Data (`t`)**:
       - Meminta data mahasiswa baru dan menambahkannya ke daftar.
     - **Lihat Data (`l`)**:
       - Menampilkan daftar mahasiswa.
     - **Ubah Data (`u`)**:
       - Meminta nama mahasiswa yang akan diubah, mencari datanya, dan memperbarui informasi.
     - **Hapus Data (`h`)**:
       - Meminta nama mahasiswa yang akan dihapus dan menghapus datanya dari daftar.
     - **Keluar (`k`)**:
       - Mengakhiri program.
   - Input pengguna diubah menjadi huruf kecil dengan `.lower()` untuk memastikan kemudahan pemrosesan.

### 6. **Blok `if __name__ == "__main__":`**
   - Memastikan bahwa fungsi `main` hanya dijalankan jika file ini dijalankan sebagai program utama, bukan diimpor sebagai modul.

# Hasil Program

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/b4c14e452d48e14b6e0af0c76741110c01fa92fa/Screenshot%202024-12-10%20203158.png)
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/b4c14e452d48e14b6e0af0c76741110c01fa92fa/Screenshot%202024-12-10%20203234.png)

# Diagram Class

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/6b1ae54f8dda9eeade2f651829611296b8072dcd/scr6.png)

# Flowchart
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/c32c66e2c93928ed56806ccd241f87484e532b3d/scr5%20(1).png)
