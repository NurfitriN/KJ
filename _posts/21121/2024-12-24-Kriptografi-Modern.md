---
title: Kriptografi Modern
category: Materi
author: Nurfitri N. Lasida (21121)
published: true
---
# KRIPTOGRAFI MODERN

## KATA PENGANTAR
  Puji Syukur Kami panjatkan kehadirat Allah SWT. Yang telah melimpahkan Rahmat dan hidayahnya sehingga Kami dapat meyelesaikan Artikel ini, yang berjudul “Kriptografi Modern” shalawat serta salam tak lupa juga kita lanturkan kepada junjungan kita Nabi besar Muhammad SAW. atas berkat perjuangannya yaitu memperjuangkan manusia dari jaman kegelapan menuju jaman terang benderang seperti sekarang ini.
Sebagai penyusun, Saya Menyadari bahwa Laporan ini masih terdapat kekurangan, baik dari penyusunan maupun tata bahasa penyampaian dalam Artikel ini Oleh karena itu, Saya mengharapkan kritik dan saran yang membangun dari para pembaca guna menyempurnakan segala kekurangan dalam penyusunan Artikel ini, Kami  juga berharap agar Laporan ini bermanfaat bagi semua pihak.

##PENDAHULUAN

  Di dunia yang semakin terhubung secara digital, keamanan data menjadi prioritas utama. Kriptografi, ilmu yang mempelajari teknik penyandian informasi, telah digunakan untuk melindungi data dan komunikasi. Ada dua jenis utama algoritma kriptografi yang sering digunakan untuk enkripsi dan dekripsi data: simetris dan asimetris. Dua algoritma yang banyak dipelajari dan diterapkan dalam kriptografi modern adalah Data Encryption Standard (DES), yang merupakan algoritma simetris, dan RSA (Rivest-Shamir-Adleman), yang merupakan algoritma asimetris.
artikel ini akan membahas kedua algoritma tersebut, mulai dari sejarah, prinsip kerja, kelebihan dan kekurangannya, serta contoh implementasi dari kedua algoritma tersebut. Pembahasan ini diharapkan dapat memberikan pemahaman yang lebih baik tentang cara kerja enkripsi menggunakan DES dan RSA serta perbandingan antara keduanya.

##PEMBAHASAN

###A. Kriptografi

  Kriptografi adalah cabang ilmu yang mempelajari tentang teknik-teknik untuk mengamankan data agar tidak dapat diakses oleh pihak yang tidak berwenang. Dalam kriptografi, terdapat dua tipe utama algoritma: algoritma simetris dan algoritma asimetris.
1. 	Kriptografi Simetris menggunakan satu kunci yang sama untuk enkripsi dan dekripsi data. Contohnya adalah DES.
2. Kriptografi Asimetris menggunakan dua kunci yang berbeda,  yaitu kunci publik untuk enkripsi dan kunci privat untuk dekripsi. Contoh dari algoritma ini adalah RSA.

###B.Data Encryption Standard (DES)

  Data Encryption Standard (DES) adalah algoritma enkripsi simetris yang dikembangkan oleh IBM pada 1970-an dan diadopsi oleh pemerintah Amerika Serikat pada tahun 1977. DES bekerja dengan mengolah data dalam blok 64-bit dan menggunakan kunci sepanjang 56-bit. Meskipun DES pernah menjadi standar enkripsi yang paling banyak digunakan, saat ini algoritma ini sudah dianggap tidak aman lagi untuk aplikasi modern karena panjang kunci yang terlalu pendek.
1. Metode Enkripsi DES

  a. Prinsip Kerja DES
  
  DES bekerja pada blok data 64-bit dan menggunakan kunci enkripsi 56-bit. Proses enkripsi dan dekripsi dalam DES terdiri dari langkah-langkah sebagai berikut:
  •	Initial Permutation (IP): Blok data 64-bit dipermutasikan.
  •	Fungsi Feistel: Blok 64-bit dibagi menjadi dua bagian 32-bit. Masing-masing bagian diproses selama 16 putaran dengan sub-kunci yang berbeda.
  •	Sub-kunci: Kunci 56-bit dibagi menjadi 16 sub-kunci, masing-masing sepanjang 48-bit.
  •	Final Permutation (FP): Setelah 16 putaran, hasilnya dipermutasikan kembali untuk menghasilkan ciphertext.

  2. Contoh Implementasi DES
  Misalkan kita ingin mengenkripsi pesan "HELLO" dengan DES. Berikut adalah langkah-langkah secara umum:
  •	Langkah 1: Konversi plaintext menjadi format biner.
  •	Langkah 2: Menggunakan kunci 56-bit untuk mengenkripsi blok 64-bit dari plaintext.
  Implementasi praktis dari DES dapat dilakukan menggunakan pustaka kriptografi seperti PyCryptodome dalam bahasa Python.

###C.RSA (Rivest-Shamir-Adleman)

  RSA adalah algoritma enkripsi asimetris yang ditemukan oleh Ron Rivest, Adi Shamir, dan Leonard Adleman pada tahun 1977. RSA bekerja dengan menggunakan dua kunci yang berbeda: kunci publik untuk enkripsi dan kunci privat untuk dekripsi. RSA memiliki tingkat keamanan yang tinggi, yang bergantung pada kesulitan faktorisasi bilangan besar. RSA banyak digunakan dalam aplikasi yang membutuhkan keamanan tinggi, seperti tanda tangan digital dan protokol SSL/TLS.
  1.  Metode Enkripsi RSA
  a. Prinsip Kerja RSA
  RSA menggunakan dua kunci: kunci publik dan kunci privat. Langkah-langkah enkripsi dan    dekripsi RSA adalah sebagai berikut:
  •	Pemilihan Dua Bilangan Prima: Pilih dua bilangan prima besar, ppp dan qqq.
  •	Menghitung Modulus nnn: n=p×qn = p \times qn=p×q.
  •	Menghitung Fungsi Euler ϕ(n)\phi(n)ϕ(n): ϕ(n)=(p−1)(q−1)\phi(n) = (p-1)(q-1)ϕ(n)=(p−1)(q−1).
  •	Menentukan Kunci Publik dan Privat: Pilih eee yang relatif prima terhadap                 ϕ(n)\phi(n)ϕ(n), dan hitung ddd, yang merupakan invers dari eee terhadap                  ϕ(n)\phi(n)ϕ(n).
  •	Enkripsi dan Dekripsi: Enkripsi dilakukan dengan rumus c=memod  nc = m^e \mod             nc=memodn, dan dekripsi dengan rumus m=cdmod  nm = c^d \mod nm=cdmodn.

  b. Contoh Implementasi RSA
  Misalkan kita memilih bilangan prima kecil untuk tujuan ilustrasi:
  •	p=61p = 61p=61, q=53q = 53q=53
  •	n=61×53=3233n = 61 \times 53 = 3233n=61×53=3233
  •	ϕ(n)=(p−1)(q−1)=3120\phi(n) = (p-1)(q-1) = 3120ϕ(n)=(p−1)(q−1)=3120
  •	Pilih e=17e = 17e=17, dan hitung d=2753d = 2753d=2753 sebagai invers dari eee.
    Proses enkripsi untuk pesan m=65m = 65m=65 dilakukan dengan rumus c=memod  nc = m^e \mod nc=memodn, yang menghasilkan ciphertext 2790. Dekripsi dilakukan dengan menggunakan kunci privat d=2753d = 2753d=2753, menghasilkan pesan asli m=65m = 65m=65.

###D. Perbandingan DES dan RSA

1. itur	DES
Jenis Algoritma	Simetris
Panjang Kunci	56-bit
Kecepatan	Cepat, cocok untuk volume data besar
Keamanan	Rentan terhadap brute force
Aplikasi	Enkripsi data dalam jumlah besar
Kelemahan	Kunci pendek, rentan terhadap serangan brute force

2. Fitur RSA
Jenis Algoritma Asismetris
Panjang Kunci 1024-bit, 2048-bit, atau lebih besar
Kecepatan Lambat, cocok untuk tanda tangan digital dan enkripsi kunci
Keamanan Keamanan tinggi, rentan terhadap komputasi kuantum
Aplikasi Enkripsi kunci, tanda tangan digital
Kelemahan Proses enkripsi lambat, kunci besar

###KESIMPULAN

Kriptografi memiliki peran yang sangat penting dalam melindungi keamanan data di era digital. DES, meskipun cepat, kini sudah dianggap tidak aman karena panjang kuncinya yang hanya 56 bit, yang membuatnya rentan terhadap serangan brute force. Di sisi lain, RSA menawarkan tingkat keamanan yang lebih tinggi dengan menggunakan kunci publik dan privat, meskipun lebih lambat dan memerlukan kunci yang lebih panjang. Dalam aplikasi modern, DES telah digantikan oleh algoritma yang lebih aman seperti AES, sementara RSA tetap relevan untuk berbagai aplikasi yang memerlukan tingkat keamanan tinggi, seperti tanda tangan digital dan enkripsi komunikasi.

## DAFTAR PUSTAKA 
1.	Stallings, W. (2017). Cryptography and Network Security: Principles and Practice (7th ed.). Pearson Education.
2.	Schneier, B. (1996). Applied Cryptography: Protocols, Algorithms, and Source Code in C (2nd ed.). John Wiley & Sons.
3.	Rivest, R. L., Shamir, A., & Adleman, L. (1978). A Method for Obtaining Digital Signatures and Public-Key Cryptosystems. Communications of the ACM, 21(2), 120-126. DOI: 10.1145/359340.359342.
4.	Ferguson, N., Schneier, B., & Kohno, T. (2010). Cryptography Engineering: Design Principles and Practical Applications. Wiley.
5.	NIST. (2001). FIPS PUB 46-3: Data Encryption Standard (DES). National Institute of Standards and Technology. https://csrc.nist.gov/publications/detail/fips/46/3/final.












 

