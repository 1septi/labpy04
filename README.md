# labpy04
Nama : Ika Septianingrum
IE.23.C12/ 352310873

Program Pengolah Data Nilai Akhir Mahasiswa

Deskripsi Program

Program ini dibuat untuk mencatat data nilai akhir mahasiswa, data ini menghitung nilai akhir berdasarkan tiga komponen nilai yaitu nilai Tugas, nilai UTS, dan nilai UAS dengan presentase nilai yang sudah ditentukan. Program ini dapat digunakan secara berulang hingga pengguna memutuskan untuk berhenti menambahkan data.

Langkah-langkah menggunakan program

1. Mulai: Program dimulai.
2. Input Nama Mahasiswa: Program meminta nama mahasiswa dan NIM.
   Program dimulai dengan mendefinisikan data_mahasiswa sebagai list kosong yang akan menyimpan data mahasiswa.
3. Input Nilai: Program meminta nilai tugas, UTS, dan UAS.
   Program akan terus meminta input nama mahasiswa dan nilai-nilai tugas, UTS, dan UAS menggunakan perulangan while True. Setiap kali data dimasukkan, program akan menghitung nilai akhir dan menyimpannya dalam list data_mahasiswa.
4. Validasi Input: Program memeriksa apakah nilai yang dimasukkan valid.
   Jika tidak valid, program meminta input ulang. Program menggunakan try-except untuk menangani kesalahan input (misalnya jika input bukan angka).
5. Hitung Nilai Akhir: Nilai akhir dihitung dengan rumus bobot.
   Fungsi ini digunakan untuk menghitung nilai akhir dari mahasiswa berdasarkan bobot nilai tugas (30%), UTS (35%), dan UAS (35%).
6. Simpan Data: Data mahasiswa disimpan dalam list.
7. Pertanyaan Tambah Data: Program menanyakan apakah pengguna ingin menambah data lagi.
   Jika 'y', kembali ke langkah 2.
   Jika 't', lanjut ke langkah 8.
8. Setelah memasukkan data, program akan menanyakan kepada pengguna apakah ingin menambah data lagi dengan input 'y' atau 't'. Jika input 't' dimasukkan, perulangan akan berhenti.
9. Tampilkan Data: Program menampilkan semua data mahasiswa beserta nilai akhir.
    Setelah perulangan berhenti, program akan menampilkan seluruh data mahasiswa yang telah dimasukkan beserta nilai akhir mereka.
10. Selesai: Program selesai.
    Program akan menampilkan tabel berisi perhitungan nilai



Flowchart Program

![Capture flowchart JPG (2)](https://github.com/user-attachments/assets/1792492a-b6e3-49be-bbc5-1ac5fa7194b4)



Hasil Praktikum

![Capture komputer ](https://github.com/user-attachments/assets/c38d0c92-c427-4281-81a6-c066ef389160)
