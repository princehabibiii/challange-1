##  Challenge 1
Information Disclosure – Sensitive File Exposure

### Description:
Sebagai External Security Consultant, peserta ditugaskan untuk memverifikasi dugaan kebocoran informasi pada platform e-commerce PT. Mencari Cinta Sejati. Fokus pengujian pada tahap ini adalah mengidentifikasi adanya data internal aplikasi yang masih tersimpan dan dapat diakses, meskipun tidak ditampilkan secara eksplisit pada antarmuka pengguna (UI) utama aplikasi.

### Hint: 
Mata uang digital terlupakan menunggu di balik kode. Jejak lama masih tersimpan dalam jantung aplikasi, namun tak terlihat di permukaan. Gali lebih dalam, temukan alamat yang ditinggalkan, dan ikuti jalan yang tersembunyi. Redirect.

### Analysis:
Hint yang diberikan mengarah pada konsep mata uang digital, yang dapat diasosiasikan dengan cryptocurrency seperti Bitcoin atau teknologi blockchain. Frasa “jejak lama masih tersimpan dalam jantung aplikasi” mengindikasikan bahwa informasi sensitif kemungkinan masih tertanam di dalam source code aplikasi, meskipun tidak lagi digunakan secara aktif atau ditampilkan pada UI.

Selain itu, kata “tak terlihat di permukaan” menegaskan bahwa informasi tersebut tidak dapat ditemukan melalui navigasi normal website dan membutuhkan analisis lebih dalam terhadap struktur halaman, khususnya pada sisi client-side seperti HTML dan JavaScript. Petunjuk “Redirect” mengarah pada kemungkinan adanya URL tersembunyi atau endpoint lama yang masih dapat diakses.

### Solution:
1. Mengakses halaman utama aplikasi e-commerce
![image alt](https://github.com/princehabibiii/challange-1/blob/main/s1.jpeg?raw=true)

2. Melakukan inspeksi elemen halaman menggunakan fitur Inspect Element pada browser.
![image alt](https://github.com/princehabibiii/challange-1/blob/main/s2.jpeg?raw=true)

3. Menelusuri struktur HTML dan JavaScript yang dimuat pada halaman utama.

4. Mengidentifikasi komentar, variabel, atau potongan kode yang berkaitan dengan petunjuk redirect.
![image alt](https://github.com/princehabibiii/challange-1/blob/main/s4.jpeg?raw=true)

5. Menemukan referensi URL tersembunyi yang berkaitan dengan mata uang digital atau blockchain.
![image alt](https://github.com/princehabibiii/challange-1/blob/main/s5.jpeg?raw=true)

6. Mengakses URL tersebut secara langsung melalui browser.
7. Setelah halaman berhasil diakses, ditemukan data unik yang berfungsi sebagai flag, yang membuktikan adanya kebocoran informasi.
![image alt](https://github.com/princehabibiii/challange-1/blob/main/1111.jpeg?raw=true)


### Flag:
2157c550eb430a772b20462a71e8c049dc5b95cc
