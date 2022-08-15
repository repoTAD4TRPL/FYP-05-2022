# FYP-05-2022
Project repository for group 05

# TA2_05

Topik Proyek: Machine Learning

Nama Sistem atau Aplikasi : “Penerapan Sentiment Analysis pada Review Menggunakan Metode Support Vector Machine dan Bidirectional Encoder Representations from Transformers”

Jenis Sistem atau Aplikasi (Desktop/ Mobile/ Web, dll): Google Colab

Persiapan, mencakup: 
Lingkungan  yang  digunakan  dalam  implementasi  Tugas  Akhir  ini  mencakup lingkungan perangkat keras dan perangkat lunak  yang digunakan dalam implementasi. Spesifikasi perangkat keras yang digunakan untuk implementasi adalah sebagai berikut.
1.	Spesifikasi hardware lingkungan operasional aplikasi antara lain:
    a.	PC type : Lenovo.
    b.	Processor : Intel(R) Core(TM) i5-7200U CPU @2.50 GHz (4 CPUs), ~2.7GHz
    c.	Memory : 8.00 GB 
    d.	OS : Windows 10
2.	Spesifikasi software lingkungan operasional aplikasi antara lain:
    a.	Tools Pengembang : Jupyter Notebook, Google Colaboratory
    b.	Programming Language :  Python
    c.	Database : MySQL

Langkah-langkah menjalankan aplikasi web atau mobile tersebut. Jelaskan dengan detail mulai dari download source code  dari github, hingga proses instalasi berhasil dijalankan. Gunakan kalimat yang benar dan gambar yang sesuai.
Cara Download Repositori:

A. Cara download repository di GitHub secara langsung menjadi .zip:
1. Pastikan Anda di halaman repositori GitHub yang ingin diunduh.
2. Klik tombol ‘Code’ yang berwarna hijau.
3. Klik ‘Download ZIP’.
4. Repositori GitHub sudah tersimpan dalam direktori download di komputer Anda.
5. Setelah itu ekstrak  Repositori tersebut.

B. Cara git clone menggunakan Git Bash
Berikut cara git clone atau cara men-download suatu repository menggunakan Git Bash:
1. Kunjungi halaman repositori yang ingin di-clone ke komputer Anda.
2. Klik tombol ‘Code’ yang berwarna hijau.
3. Salin (copy) teks yang ada di dalam kotak. Teks ini merupakan alamat web dari halaman repositori. Kami sarankan Anda untuk mencatat teks ini.
4. Buka folder tempat Anda ingin menyimpan repositori di komputer.
5. Klik kanan pada folder tersebut, kemudian pilih Git Bash Here.
6. Ketik git clone, kemudian tempel (paste) teks yang tadi disalin. (Tip: untuk mem-paste di command prompt seperti ini, tekan Shift+Insert atau Shift+Ins secara bersamaan)
7. Tekan Enter, maka Git akan mulai men-download repositori tersebut. Anda dapat menunggu sampai seluruh file selesai diunduh.

Setelah selesai Download Repositori, selanjutnya adalah menjalankan sistemnya. Machine learningnya dapat dijalankan pada Google Colaboratory dan Jupyter notebook:

A. Google Colaborator
1. Buka drive.google.com.
2. Di kiri atas, klik Baru lalu  Upload File atau Upload Folder.
3. Pilih file atau folder yang ingin diupload. 
4. Setelah itu klik button Baru di drive
5. Klik lainnya, pilih "hubungkan aplikasi lainnya"
![image](https://user-images.githubusercontent.com/60635181/184630482-85e9c186-9ca6-4cad-a737-c2c79fb8d448.png)
6. Pada kotak pencarian ketik "Google Colab" dan klik install
![image](https://user-images.githubusercontent.com/60635181/184630638-7153cb7e-5887-49ba-bfc7-56f2720cf7f2.png)

Setelah folder terpuload, maka selanjutnya kita dapat menjalankan machine learningnya:
1. Sistem yang akan di run terdapat pada folder BERT dan SVM
2. Pertama kita menjalankan metode SVM di folder SVM
![image](https://user-images.githubusercontent.com/60635181/184631445-df349bb4-8f4f-4bac-addb-be0483450de9.png)
4. Buka salah satu file yang ada  pada folder tersebut
5. Pilih icon files, klik upload files. Upload dataset "ebay reviews.csv"
![image](https://user-images.githubusercontent.com/60635181/184631515-03817564-abc1-4bca-82f5-f01840b1fef8.png)
6. Copy path tempat dataset yang upload ke cell berikut
![image](https://user-images.githubusercontent.com/60635181/184631322-f4bcab4e-5d8c-49bd-bf8e-4a2bd295b994.png)
7. Kemudian  pilih menu runtime  pilih "run all"
![image](https://user-images.githubusercontent.com/60635181/184631381-3d394437-2014-4ede-ac5f-e56de6bb39bc.png)
8. Langkah 1-6 dapat dilakukan pada semua file yang ada di folder BERT dan SVM

B. Jupyter notebooK
1. Masuk ke halaman website https://www.python.org/downloads/ untuk mendownload Python
2. Pilih jenis sistem operasi yang kamu gunakan. (Windows, Linux/UNIX, Mac OS X, Other). Untuk pc/laptop dengan OS Windows 10, klik Windows.
![image](https://user-images.githubusercontent.com/60635181/184634928-2a24cfe4-e59d-4f2f-afd0-9cd8b5e9e6cb.png)

3. Pilih versi rilis Python yang ingin kamu download. Pemilihan versi ini dapat disesuaikan dengan kebutuhan masing-masing. Di sini saya mendownload Python versi 3.8.  ![image](https://user-images.githubusercontent.com/60635181/184634991-1acb63bb-9ee9-4ac8-a27c-0b0e72f42e27.png)

4. Pilih version “Windows x86–64 executable installer”. Proses download akan berjalan dan tunggu hingga selesai  ![image](https://user-images.githubusercontent.com/60635181/184640633-5b00b9dc-5a02-4068-bf2a-7534fca6b6e7.png)

5. Setelah proses download selesai, buka installer dan klik tombol Run. Jangan lupa untuk memilih opsi menambahkan Python 3.8 ke PATH dan Install launcher for all users sebelum mengklik tombol “Install Now”
6. Ketika proses instalasi telah selesai, pilih opsi “Disable path length limit” dan tutup proses instalasi Python dengan mengklik tombol Close
7. Setelah melakukan instalasi, cek apakah Python sudah terinstall dengan baik melalui jendela Command Prompt. Untuk membuka jendela Command Prompt dapat dilakukan dengan mengetikkan “Command Prompt” pada fitur Search.
8. Kemudian akan muncul jendela sebagai berikut
9. Tulis perintah: python –version. Jika Python telah terinstall, maka Command Prompt akan menampilkan versi Python tersebut.   
![image](https://user-images.githubusercontent.com/60635181/184640831-48a43787-00c3-4e21-926a-f931e9820252.png)

10. Jika langkah 7 gagal, buka Environment Variables dengan cara mengetikkannya pada fitur Search di taskbar untuk menambahkan path python secara manual.
11. Kemudian klik tombol Environment Variables
12. Cari variabel Path pada jendela System Variable. Kemudian klik Edit.
13. Klik New untuk menambahkan Path. Kemudian tuliskan lokasi folder instalasi dan klik OK.
14. Untuk menjalankan Jupyter Notebook, ketikkan perintah “jupyter notebook” pada Command Prompt dan tekan Enter. Kemudian akan tampil jendela sebagai berikut.  
![image](https://user-images.githubusercontent.com/60635181/184641267-1b4741c0-403a-4c8d-a80d-e601e6156867.png)

15. Klik “New > Python 3” untuk membuka notebook baru. Dan sekarang Jupyter Notebook mu siap digunakan untuk mengeksplor data
![image](https://user-images.githubusercontent.com/60635181/184641338-83bb829c-8c6a-4c0f-bd2b-bb9d9d89250a.png)

16.  Kemudian  pilih menu kernel  pilih "restrat run all"
![image](https://user-images.githubusercontent.com/60635181/184641674-7c4cc93f-ee6e-4696-ae86-50ff43a1746d.png)
