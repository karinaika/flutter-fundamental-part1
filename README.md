# 📱 Laporan Praktikum Pemrograman Mobile  

## Jobsheet 4 Flutter 1: Aplikasi Pertama dan Widget Dasar Flutter  

---

## 🙋‍♀️ Identitas  
- **Nama**  : Karina Ika Indasa  
- **NIM**   : 2341760042  
- **Kelas** : SIB-3C  
- **Mata Kuliah** : Pemrograman Mobile  

---

## 🎯 Tujuan Praktikum  
1. Mengenal struktur dasar project Flutter.  
2. Mampu membuat aplikasi pertama menggunakan Flutter.  
3. Memahami dan menggunakan widget dasar pada Flutter. 
4. Menjalankan aplikasi pada perangkat fisik (Android/iOS). 

---

## 🛠️ Alat dan Bahan
- **Hardware** : Laptop/PC dengan RAM minimal 8GB  
- **Software** :
  - Flutter SDK  
  - Android Studio / VS Code  
  - Emulator Android / Device Fisik  
- **Bahasa Pemrograman** : Dart  

--- 

## 📝 Langkah Praktikum  
### Praktikum 1: Membuat Project Flutter Baru
**Langkah 1:**
- Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project. 

  ![new_flutter](images/P1langkah1.png)

**Langkah 2:**
- Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

  ![new_flutter](images/P1langkah2.png)

**Langkah 3:**
- Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.

  ![new_flutter](images/P1langkah3.png)

**Langkah 4:**
- Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.

  ![new_flutter](images/P1langkah4.png)

### Praktikum 2: Menghubungkan Perangkat Android atau Emulator
- Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

  https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0

### Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum
**Langkah 1:**
- Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"

  ![new_flutter](images/P3langkah1.png)

**Langkah 2:**
- Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.

  ![new_flutter](images/P3langkah2.png)

**Langkah 3:**
- Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

  ![new_flutter](images/P3langkah3.png)

**Langkah 4:**
- Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.

  ![new_flutter](images/P3langkah4.png)

**Langkah 5:**
- Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

  ![new_flutter](images/P3langkah5.png)

**Langkah 6:**
- Lakukan push dengan klik bagian menu titik tiga > Push

  ![new_flutter](images/P3langkah6.png)

**Langkah 7:**
- Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"

  ![new_flutter](images/P3langkah7.png)

**Langkah 8:**
- Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

  ![new_flutter](images/P3langkah8_1.png)

- Setelah berhasil, tulis remote name dengan "origin"

  ![new_flutter](images/P3langkah8_2.png)

**Langkah 9:**
- Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

  ![new_flutter](images/P3langkah9.png)

  ![new_flutter](images/P3langkah9_1.png)

**Langkah 10:**
- Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

  ![new_flutter](images/P3langkah10_1.png)

  ![new_flutter](images/P3langkah10_2.png)

**Langkah 11:**
- Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

  ![new_flutter](images/P3langkah11_1.png)

  ![new_flutter](images/P3langkah11_2.png)

**Langkah 12:**
- Silahkan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

  ![new_flutter](images/P3langkah12_1.png)

  ![new_flutter](images/P3langkah12_2.png)