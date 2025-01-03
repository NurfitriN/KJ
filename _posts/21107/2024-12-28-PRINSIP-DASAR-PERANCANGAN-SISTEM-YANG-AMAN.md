---
title: PRINSIP DASAR PERANCANGAN SISTEM YANG AMAN
category: Materi
author: Fira ABD Alim
NPM: 121055520121107
---

## Pendahuluan

Perancangan sistem yang aman adalah suatu pendekatan untuk memastikan bahwa sistem yang dibangun dapat melindungi data, menjaga integritas operasi, dan mencegah ancaman dari potensi risiko keamanan. Dalam dunia yang semakin terhubung secara digital, ancaman terhadap sistem informasi menjadi semakin kompleks dan beragam, sehingga penting untuk merancang sistem dengan memperhatikan aspek keamanan sejak awal.
Prinsip dasar dalam perancangan sistem yang aman bertujuan untuk menciptakan sistem yang tidak hanya fungsional, tetapi juga dapat mengurangi atau bahkan mengeliminasi potensi kerentanannya terhadap berbagai ancaman yang mungkin muncul. Oleh karena itu, perancangan sistem yang aman tidak hanya berkaitan dengan pemilihan perangkat keras dan perangkat lunak yang tepat, tetapi juga melibatkan aspek kebijakan, prosedur, dan kesadaran akan ancaman keamanan.

## Jenis-Jenis Prinsip Dasar Perancangan Sistem Yang Aman

1.	Prinsip Least Privilege (Prinsip Hak Akses Minimum): adalah salah satu prinsip dasar dalam keamanan informasi dan perancangan sistem yang aman yang menyatakan bahwa setiap entitas (baik itu pengguna, aplikasi, maupun proses) hanya diberikan hak akses yang minimum yang diperlukan untuk melakukan tugas atau fungsinya. Dengan kata lain, entitas tersebut hanya boleh mengakses sumber daya atau informasi yang benar-benar diperlukan untuk menjalankan tugasnya dan tidak lebih.Contohnya adalah Pemisahan Tugas: Dalam organisasi, tugas yang melibatkan akses ke data sensitif atau pengelolaan sumber daya kritis dibagi antara beberapa individu atau tim untuk memastikan tidak ada individu yang memiliki kendali penuh.

2.	Prinsip Fail-Safe Defaults (Pengaturan Keamanan Standar adalah prinsip dalam perancangan sistem yang aman yang menyarankan agar sistem dirancang dengan pengaturan keamanan default yang aman, yaitu pengaturan yang secara otomatis membatasi akses atau mematikan fungsi yang berisiko jika terjadi kesalahan atau kegagalan. Dengan kata lain, jika terjadi kegagalan sistem atau konfigurasi yang salah, sistem harus default ke kondisi yang aman, bukan kondisi yang rentan terhadap ancaman.Contohnya adalah Aplikasi Web: Aplikasi web sebaiknya mengatur pengaturan default yang membatasi akses API atau data hanya kepada pengguna yang sudah login dan terautentikasi, serta memastikan bahwa data pribadi atau kredensial tidak diungkapkan tanpa enkripsi yang memadai.


3.	Prinsip Separation of Duties (Pemisahan Tugas):. adalah prinsip dasar dalam perancangan sistem yang aman, yang bertujuan untuk membagi tugas atau wewenang tertentu kepada lebih dari satu individu atau entitas dalam suatu organisasi. Tujuan utama dari prinsip ini adalah untuk mencegah penyalahgunaan kekuasaan, penipuan, atau kesalahan yang tidak disengaja dengan memastikan bahwa tidak ada satu individu yang memiliki kontrol penuh atas seluruh proses atau sistem yang sensitif.Contohnya adalah Penyetoran uang: Satu orang bertanggung jawab untuk menerima uang tunai dan menyetor ke bank.

4.	Prinsip Open Design (Desain Terbuka adalah salah satu prinsip dasar dalam perancangan sistem yang aman yang menyatakan bahwa desain sistem harus terbuka dan tidak bergantung pada kerahasiaan desain itu sendiri untuk menjamin keamanannya. Dalam prinsip ini, mekanisme keamanan sistem tidak boleh mengandalkan kerahasiaan desain atau algoritma yang digunakan. Sebaliknya, keamanan sistem harus terjamin oleh kekuatan dan ketahanan dari desain itu sendiri, bahkan jika desain atau algoritma tersebut diketahui oleh pihak luar.Contohnya adalah Algoritma Enkripsi Terbuka: Algoritma enkripsi yang terbuka, seperti RSA dan AES, adalah contoh dari desain sistem yang terbuka. Meskipun detail tentang cara kerja enkripsi ini dapat diakses oleh publik, algoritma tersebut tetap aman jika diterapkan dengan benar, berkat kekuatan matematika yang mendasarinya dan pendekatan untuk mengatasi potensi serangan.


5.	Prinsip Minimization (Minimisasi): dalam konteks perancangan sistem yang aman, mengacu pada konsep mengurangi kompleksitas dan eksposur terhadap potensi risiko dengan cara meminimalkan jumlah komponen, fitur, dan hak akses yang diperlukan dalam suatu sistem. Dengan mengurangi jumlah elemen yang terlibat, kita mengurangi kemungkinan terjadinya kerentanannya serta mempermudah pengelolaan dan pemantauan keamanan.Contohnya adalah Pengelolaan Sistem Operasi: Pada sistem operasi server, hanya layanan yang penting dan diperlukan yang dijalankan. Sebagai contoh, jika server hanya berfungsi untuk menjalankan aplikasi web, maka layanan lain seperti FTP atau SSH yang tidak diperlukan seharusnya dimatikan atau dihapus.

6.	Prinsip Fail-Closed: adalah prinsip yang diterapkan dalam perancangan sistem yang aman, yang mengharuskan suatu sistem untuk berada dalam keadaan tertutup atau aman jika terjadi kegagalan atau kesalahan. Dalam hal ini, ketika sistem mengalami masalah, kerusakan, atau gangguan, sistem harus dirancang untuk menutup akses atau menghentikan operasional secara otomatis untuk mencegah potensi risiko keamanan yang lebih besar.



7.	Auditability (Kemampuan untuk Diaudit): adalah prinsip dasar dalam perancangan sistem yang aman yang mengacu pada kemampuan untuk memonitor, merekam, dan memverifikasi aktivitas dalam sistem secara terperinci. Dengan kata lain, sistem harus dirancang agar setiap tindakan atau perubahan yang terjadi dalam sistem dapat dilacak, diaudit, dan ditinjau kembali untuk memastikan bahwa sistem berfungsi sesuai dengan kebijakan keamanan dan tidak ada aktivitas yang mencurigakan atau melanggar aturan.Contohnya adalah Transparansi dan Akuntabilitas: Auditabilitas memungkinkan setiap tindakan dapat dipertanggungjawabkan. Ini meningkatkan transparansi dalam operasional dan memberikan kepercayaan kepada pihak terkait, seperti pelanggan atau regulator, bahwa sistem dijalankan dengan benar dan aman.

## Dampak Prinsip Dasar Perencangan Sistem Yang Aman

1.	Peningkatan Keamanan Sistem Prinsip dasar perancangan sistem yang aman seperti Least Privilege (Hak Akses Minimum), Separation of Duties (Pemisahan Tugas), dan Defense in Depth (Pertahanan Berlapis) secara langsung memperkuat ketahanan sistem terhadap serangan eksternal maupun ancaman internal. Dengan membatasi akses hanya pada pihak yang berwenang dan mengurangi kemungkinan satu titik kegagalan, sistem menjadi lebih sulit untuk dieksploitasi oleh penyerang. Dampak: Mengurangi kemungkinan kebocoran data, pencurian identitas, dan serangan yang dapat merusak integritas dan kerahasiaan informasi.

2.	Pengurangan Potensi Kerusakan akibat Kegagalan Sistem Penerapan prinsip Fail-Closed menjamin bahwa sistem akan mengunci atau menghentikan operasi secara otomatis ketika terjadi kegagalan atau kesalahan, untuk mencegah kerusakan lebih lanjut. Ini adalah langkah preventif untuk menjaga agar kerusakan tidak menyebar atau dimanfaatkan oleh pihak yang tidak berwenang. Dampak: Mengurangi potensi kerusakan besar pada sistem dan data akibat kesalahan teknis atau serangan. Sistem dapat segera menanggapi masalah dengan menghentikan operasional hingga masalah teratasi.



3.	Peningkatan Keandalan dan Kepercayaan Pengguna Dengan memastikan bahwa sistem dapat dipercaya untuk melindungi data dan informasi, serta melakukan pemantauan dan pencatatan yang cermat (seperti yang diterapkan dalam prinsip Auditability), organisasi dapat meningkatkan kepercayaan pengguna dan pelanggan. Pengguna akan merasa lebih aman menggunakan layanan jika mereka tahu bahwa akses dan aktivitas mereka diawasi dengan ketat. Dampak: Meningkatkan reputasi dan kepercayaan pelanggan terhadap organisasi, yang pada gilirannya dapat memperkuat hubungan bisnis dan meningkatkan kepuasan pengguna.

4.	Kepatuhan terhadap Regulasi dan Standar Keamanan Penerapan prinsip-prinsip dasar seperti Auditability dan Minimization membantu organisasi untuk mematuhi peraturan dan standar yang relevan, seperti GDPR, PCI DSS, atau HIPAA, yang mengatur perlindungan data pribadi dan keamanan informasi. Organisasi yang memiliki sistem yang dapat diaudit dan meminimalkan risiko kebocoran data akan lebih mudah memenuhi kewajiban hukum dan regulasi. Dampak: Mengurangi risiko sanksi hukum dan denda yang mungkin dikenakan oleh regulator jika ditemukan pelanggaran terhadap aturan yang berlaku. Juga membantu organisasi untuk tetap berada dalam jalur kepatuhan dan melindungi reputasinya.



5.	Mengurangi Risiko Penyalahgunaan dan Penipuan Dengan menerapkan prinsip Separation of Duties (Pemisahan Tugas), risiko penyalahgunaan kekuasaan atau penipuan dapat diminimalkan. Misalnya, seorang individu yang memiliki hak akses untuk memproses transaksi tidak boleh memiliki hak untuk mengubah atau menghapus catatan transaksi tersebut. Pembatasan semacam ini mencegah potensi penipuan internal. Dampak: Meminimalkan potensi penipuan dan penyalahgunaan sumber daya oleh pihak internal yang memiliki akses yang berlebihan atau tidak terkendali.

6.	Efisiensi Pengelolaan dan Pemeliharaan Sistem Prinsip Minimization (Minimisasi) membantu mengurangi kompleksitas sistem dengan hanya mempertahankan elemen yang benar-benar diperlukan. Ini mempermudah pemeliharaan, pengelolaan, dan pengawasan sistem secara keseluruhan, serta mengurangi titik kegagalan yang mungkin terjadi. Dampak: Mengurangi biaya pemeliharaan dan operasi, serta meningkatkan kinerja dan kecepatan respons sistem terhadap permasalahan atau ancaman. Sistem yang lebih sederhana lebih mudah dipelihara dan dikelola secara efisien.



7.	Pengurangan Biaya dan Kerugian akibat Insiden Keamanan Penerapan prinsip Defense in Depth (Pertahanan Berlapis) mengharuskan sistem memiliki beberapa lapisan pengamanan yang berfungsi secara bersamaan. Jika satu lapisan gagal, lapisan lainnya dapat mengurangi dampak serangan atau mencegahnya sepenuhnya. Ini mengurangi kemungkinan terjadinya insiden keamanan yang merugikan dan biaya yang terkait dengan pemulihan atau penanggulangan insiden tersebut. Dampak: Mengurangi biaya yang dikeluarkan untuk pemulihan dari serangan atau insiden keamanan, serta meminimalkan dampak finansial dan reputasi yang bisa timbul akibat kebocoran data atau kerusakan lainnya

8.	Perlindungan Data Sensitif Dengan prinsip Open Design (Desain Terbuka), di mana desain sistem tidak bergantung pada kerahasiaan untuk mempertahankan keamanannya, serta Minimization, di mana hanya data yang perlu yang disimpan dan diolah, organisasi dapat memastikan bahwa data sensitif dilindungi dengan baik. Data yang tidak diperlukan tidak akan disimpan, dan data yang sensitif akan memiliki proteksi yang kuat Dampak: Menjaga kerahasiaan dan integritas data pribadi serta informasi sensitif, serta mengurangi kemungkinan kebocoran atau pencurian data.

## Upaya Pencegahan Prinsip Dasar Perancangan Sistem Yang Aman
1. Identifikasi dan Penilaian Risiko adalah langkah penting dalam perancangan sistem yang aman, yang bertujuan untuk mengidentifikasi potensi ancaman dan kerentanannya, serta menilai dampak dan kemungkinan terjadinya ancaman tersebut. Proses ini membantu organisasi untuk mengalokasikan sumber daya secara lebih efektif untuk mengurangi risiko yang dapat mempengaruhi keberhasilan dan keamanan sistem.
2. Prinsip Least Privilege (atau Prinsip Hak Akses Terendah) adalah salah satu prinsip keamanan yang sangat penting dalam desain sistem yang aman. Prinsip ini menyarankan bahwa setiap entitas (pengguna, aplikasi, proses, atau sistem) hanya diberikan akses yang paling minimum dan terbatas yang diperlukan untuk menjalankan tugas atau fungsinya. Dengan menerapkan prinsip ini, risiko keamanan dapat dikurangi secara signifikan, karena jika entitas tersebut disusupi atau mengalami kesalahan, dampak yang ditimbulkan akan lebih kecil.

Kesimpulan
prinsip dasar perancangan sistem yang aman adalah bahwa desain sistem yang aman memerlukan pendekatan yang holistik dan menyeluruh untuk melindungi data, mencegah gangguan, dan memastikan integritas sistem. Dalam perancangan sistem yang aman,

## Referensi
    
1.	ISO/IEC 27001 - Sistem Manajemen Keamanan Informasi (ISMS)
2.	NIST SP 800-53 - Security and Privacy Controls for Information Systems and Organizations
3.	OWASP Top 10 Open Web Application Security Project (OWASP)
4.	 CIS Controls Center for Internet Security (CIS)
5.	Principles of Information Security" oleh Michael E. Whitman dan Herbert J. Mattord
6.	Security Engineering: A Guide to Building Dependable Distributed Systems" oleh Ross Anderson
7.	The Web Application Hacker's Handbook" oleh Dafydd Stuttard dan Marcus Pinto





