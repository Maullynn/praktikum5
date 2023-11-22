![Screenshot (248)](https://github.com/Maullynn/praktikum5/assets/144296695/11ecd21c-f02b-48ef-81a6-a94cfaaca33e)## praktikum5
| Variable       |    DATA DIRI     |
| ---------------| ---------------- |
| Nama           | Muhammad Maulana |                                       
| NIM            | 312310475        |
| Kelas          | TI.23.A.5        |
| Mata Kuliah    |Bahasa Pemrograman|

## Installation environmet virtual(venv) & Deactivate di visual studio code
- python - m venv praktikum3
- for activate praktikum3/Scripts/activate
- deactivate
## Operating System Used
* [WINDOWS 10](https://www.microsoft.com/software-download/windows10) -You can use this page to download a disc image (ISO file) that can be used to install or reinstall Windows 10.
## command 
 - git add dapat digunakan secara spesifik untuk file tertentu atau direktori, memberikan Anda fleksibilitas untuk memilih perubahan mana yang akan dimasukkan dalam staging 
  area.
 - git commit -m “hi” Untuk menyimpan perubahan yang ada kedalam database repository local
 - git remote add origin https://github.com/Maullynn/praktikum4.git Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada 
   local repository, sehingga dapat diakses oleh banyak user.
 - git push -u origin master/main Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
 - git clone [url] Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working 
   directory).
## LATIHAN
  1. Pembuatan Dictionary 
  kontak = {}
  kontak["Ari"] = "081267888"
  kontak["Dina"] = "087677776"
  Program ini membuat dictionary kosong kontak, kemudian menambahkan dua entri: "Ari" dengan nomor "081267888" dan "Dina" dengan nomor "087677776".
  2. Akses Nilai dalam Dictionary
     print("Kontak Ari: ", kontak["Ari"])
      Menampilkan nomor kontak untuk nama "Ari".
  3. Penambahan dan Pembaruan Nilai
     kontak["Riko"] = "087654544"
     kontak["Dina"] = "088999776"
     Menambahkan entri baru untuk "Riko" dan memperbarui nomor untuk "Dina"
  4 Menambahkan entri baru untuk "Riko" dan memperbarui nomor untuk "Dina"
     print("\nSemua Nama: ")
     for nama in kontak:
    print(nama)

     print("\nSemua Nomor: ")
     for nomor in kontak.values():
    print(nomor)

    print("\nDaftar Nama dan Nomor: ")
    for nama, nomor in kontak.items():
    print(nama, "|", nomor)
    Menggunakan loop untuk menampilkan semua nama, semua nomor, dan daftar      nama beserta nomornya dalam dictionary.
  5. del kontak["Dina"]
    Menghapus entri untuk "Dina" dari dictionary.
  6. Menampilkan Dictionary Setelah Penghapusan
    print("\nDaftar Kontak Setelah Dihapus: ")
    for nama, nomor in kontak.items():
    print(nama, "|", nomor)
    Menampilkan daftar kontak setelah entri "Dina" dihapus.
## OUTPUT
![Screenshot (250)](https://github.com/Maullynn/praktikum5/assets/144296695/40467e84-bf0d-4e69-b9f1-f41b62431d95)


## PRAKTIKUM
1. **Fungsi Tambah Data (`tambah_data`):**
   - Meminta input NIM, nama, nilai tugas, nilai UTS, dan nilai UAS dari pengguna.
   - Menghitung nilai akhir berdasarkan bobot tertentu.
   - Menambahkan data mahasiswa ke dalam dictionary `data_mahasiswa`.

2. **Fungsi Tampilkan Data (`tampilkan_data`):**
   - Membuat tabel menggunakan PrettyTable untuk menampilkan data mahasiswa.
   - Jika data mahasiswa tidak ada, mencetak pesan bahwa data kosong.

3. **Fungsi Ubah Data (`ubah_data`):**
   - Meminta input NIM mahasiswa yang ingin diubah datanya.
   - Jika NIM tersebut ditemukan, meminta input nilai baru untuk tugas, UTS, dan UAS.
   - Menghitung nilai akhir baru.
   - Mengubah data mahasiswa yang sesuai.

4. **Menu Utama:**
   - Dalam blok `if __name__ == "__main__":`, program membuat dictionary kosong `data_mahasiswa`.
   - Menampilkan menu pilihan kepada pengguna (tambah data, ubah data, hapus data, tampilkan data, cari data, keluar).
   - Menggunakan loop untuk terus menampilkan menu dan menerima input pengguna sampai pengguna memilih keluar (`6`).

Program ini memanfaatkan dictionary untuk menyimpan data mahasiswa dan PrettyTable untuk menyajikan data dalam bentuk tabel yang terstruktur. Jadi, pengguna dapat menambah, mengubah, dan menampilkan data mahasiswa dengan lebih mudah dan terorganisir.
## OUTPUT
![Screenshot (248)](https://github.com/Maullynn/praktikum5/assets/144296695/d445bc3f-bd01-4652-b0f3-f4f1c3789a54)




