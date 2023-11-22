## praktikum5
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
## output
![Uploading Screenshot (250).png…]()

## PRAKTIKUM




