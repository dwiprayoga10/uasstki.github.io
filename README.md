# Aplikasi Analisis Sentimen Twiter
Nama : Dwi Prayoga <br/>
NIM  : A11.2022.14739 <br/>

# Tugas Akhir Sistem Temu Kembali Informasi
## 1.Dataset
Untuk Dataset yang saya gunakan diperoleh dari proses crawl twiter menggunakan Auth token.<br/>
[pemilu2024 (1).csv](https://github.com/dwiprayoga10/uasstki.github.io/files/13985672/pemilu2024.1.csv)
### Projek Ini menggunakan Library/Pustaka
  a. Twitter-php https://github.com/dg/twitter-php <br/>
  b. Sastrawi https://github.com/sastrawi/sastrawi  <br/>
  c. PHPID sentianalysis https://github.com/yasirutomo/php-sentianalysis-id <br/>

## 2.Permasalahan dan Tujuan Eksperimen
kita semua tahu bahwa pada tanggal 12 februari nanti negara kita akan mengadakan pemilihan umum,dimana salah satunya adalah pemilihan presiden dan wakil presiden.
hal ini tentunya ramai untuk dibahas oleh warganet di aplikasi twiter atau sekarang sudah berganti nama menjadi x.aplikasi X saat ini menjadi salah satu aplikasi
populer yang digunakan oleh masyarakat dalam memberikan kesan dan pendapatmya, baik opini yang bersifat positif, negatif maupun netral. Pendapat masyarakat yang 
beragam di aplikasi X ini dapat dijadikan sebagai bahan acuan untuk mendapatkan tingkat kepuasan masyarakat pada siapa saja yangberpartisipasi pada kontestasi Pemilu tersebut.Namun bagaimana cara untuk mengolah data tersbut agar dapat diketahui nilainya berupa positif,negatif,atau netral?

Oleh karena itulah saya membuat aplikasi analis sentimen aplikasi x ini.Analisis sentimen adalah proses menganalisis teks digital untuk menentukan apakah nada emosional pesan tersebut positif, negatif, atau netral.

## 3. Model dan Alur tahapan Eksperimen
Pada projek ini sistem analisis sentimen dibuat dengan menggunakan Algoritma TF-IDF dan SentiStrength Langkah-langkah pada penelitian yaitu, 
pertama crawling data Twitter menggunkaan API Twitter, kedua preprocessing, ketiga melakukan spell correction keempat Pembobotan kata (TF-IDF) 
dan terakhir klasifikasi SentiStrength, dimana hasil klasifikasi tweet memiliki sentimen positif, negatif atau netral

## 4.  Performa Model / Uji Performa Model

Contoh Screenshot Deployment <br/>
![Screenshot (651)](https://github.com/dwiprayoga10/uasstki.github.io/assets/113033658/a05b45ee-2ae5-484e-a9a9-bc65cd77442d)
![Screenshot (652)](https://github.com/dwiprayoga10/uasstki.github.io/assets/113033658/65f8755b-279b-480e-b305-5827ad3bb9db)
![Screenshot (653)](https://github.com/dwiprayoga10/uasstki.github.io/assets/113033658/161d4cf7-bf5d-47a4-9a6b-b862da17b453)
![Screenshot (654)](https://github.com/dwiprayoga10/uasstki.github.io/assets/113033658/f0c7b790-0cf5-4c90-b0e9-80f9015303a5)
