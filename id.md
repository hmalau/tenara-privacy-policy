# Kebijakan Privasi Tenara

[Read in English](./)

**Tanggal berlaku:** 5 Mei 2026
**Terakhir diperbarui:** 5 Mei 2026

## Tentang dokumen ini

Kebijakan privasi ini menjelaskan bagaimana Tenara menangani informasi ketika Anda dan anak Anda menggunakan aplikasi Tenara. Tenara diterbitkan oleh PT Bitpoin Teknologi Cakrawala, sebuah perusahaan yang terdaftar di Indonesia dengan alamat Jl. CBD Blok J9 No. 1, Bintaro Jaya Sektor 9, Kota Tangerang Selatan, Banten 15229, Indonesia. Kami adalah Pengendali Data Pribadi untuk setiap data pribadi yang dijelaskan dalam kebijakan ini.

Jika ada hal yang kurang jelas dalam dokumen ini, atau Anda memiliki pertanyaan tentang cara kami menangani data, kirim email ke prelaunchsupport.tenara@gmail.com.

## Siapa yang menggunakan Tenara

Tenara adalah aplikasi pendamping orang tua. Orang tua atau pengasuhlah yang memasang aplikasi, mengaturnya, menambahkan video ke pustaka, melakukan pembelian, dan mengoperasikan kontrol aplikasi. Anak adalah penonton konten YouTube yang diputar oleh aplikasi, dan kamera depan mengamati anak selama sesi tayang untuk memperkirakan jarak. Anak tidak masuk akun, tidak membuat akun, tidak menavigasi aplikasi, dan tidak memasukkan informasi pribadi.

## Versi singkat

Tenara hanya memproses apa yang dibutuhkan, menjalankan deteksi pada perangkat Anda alih-alih mengirim data ke server kami, dan tidak mengumpulkan informasi pribadi seperti nama, alamat email, login akun, foto, video, rekaman suara, atau data wajah tersimpan dari Anda atau anak Anda. Kami menerima aktivitas aplikasi dan laporan kerusakan yang bersifat pseudonim dan terbatas melalui Firebase, yang tidak terhubung langsung dengan identitas Anda. Sisanya adalah perinciannya.

## Kamera dan deteksi wajah

Tenara menggunakan kamera depan untuk memperkirakan jarak antara anak Anda dan layar selama sesi tayang. Kamera mendeteksi apakah ada wajah dan di mana posisi mata berada, kemudian mengubah posisi tersebut menjadi perkiraan jarak dalam sentimeter. Ini adalah deteksi wajah, bukan pengenalan wajah. Tidak ada orang tertentu yang diidentifikasi, tidak ada templat biometrik yang dibuat, dan tidak ada perbandingan dengan basis data mana pun. Seluruh pemrosesan berjalan di perangkat Anda menggunakan model di perangkat (on-device). Tidak ada gambar, frame video, atau koordinat titik wajah yang disimpan, dikirim, atau dibagikan kepada siapa pun. Kamera hanya aktif selama sesi tayang dan dapat dimatikan melalui Pengaturan. Perkiraan jarak bersifat sementara dan digunakan hanya selama sesi tayang untuk menentukan apakah pengingat perlu ditampilkan.

Nilai jarak yang ditampilkan oleh Tenara adalah perkiraan yang dihasilkan oleh teknologi penglihatan komputer, bukan pengukuran presisi. Nilai tersebut ditujukan untuk mendorong kebiasaan menonton yang nyaman, bukan untuk memberikan panduan medis atau panduan optometri.

## Rekaman suara

Jika Anda merekam pengingat suara kustom, rekaman tersebut tersimpan hanya di perangkat Anda. Rekaman digunakan untuk memutar pengingat Anda selama sesi tayang ketika sistem menilai pengingat tersebut tepat untuk diputar. Rekaman suara tidak pernah digunakan dalam urutan penutup sesi, tidak pernah dikirim ke server kami (Tenara tidak menjalankan server yang menerima konten pengguna), dan tidak pernah dibagikan kepada siapa pun. Ketika Anda menghapus rekaman dari aplikasi, rekaman tersebut langsung dihapus dari perangkat Anda.

Mikrofon hanya aktif ketika Anda memilih untuk merekam pengingat. Mikrofon tidak aktif selama sesi tayang anak.

## Apa yang kami terima melalui Firebase

Tenara menggunakan Firebase Analytics dan Firebase Crashlytics, keduanya disediakan oleh Google LLC, untuk memahami bagaimana aplikasi digunakan dan untuk mendeteksi masalah teknis.

Melalui Firebase kami menerima ID instalasi aplikasi yang bersifat pseudonim dan dihasilkan secara acak ketika aplikasi dipasang. ID ini tidak terhubung dengan nama, email, nomor telepon, akun Google, atau informasi pengenal lain milik Anda. Kami juga menerima versi aplikasi, versi sistem operasi Android, model dan kelas perangkat, setelan bahasa (locale), dan perkiraan wilayah. Google dapat menggunakan alamat IP saat penerimaan data untuk memperkirakan wilayah tersebut, tetapi Tenara tidak menerima alamat IP dalam laporan Firebase yang tersedia bagi kami.

Peristiwa interaksi yang terbatas memberi tahu kami hal-hal seperti layar mana yang dibuka, apakah sesi dimulai atau berakhir secara normal, dan apakah pembelian berhasil atau gagal. Kami telah mengonfigurasi Tenara untuk tidak pernah mengirim judul atau ID video YouTube apa pun, durasi atau isi rekaman suara apa pun, atau pengukuran apa pun dari pemeriksaan jarak kamera depan.

Laporan kerusakan mencakup tumpukan panggilan (call stack) pada saat kerusakan terjadi dan konteks dasar seperti layar mana yang aktif. Laporan kerusakan tidak mencakup metadata video, rekaman suara, atau pengukuran jarak.

Data Firebase digunakan hanya untuk operasi internal aplikasi, termasuk pemeliharaan aplikasi, keandalan, diagnosis gangguan teknis, dan pemahaman dasar tentang penggunaan aplikasi. Data tersebut tidak digunakan untuk iklan, pembuatan profil anak, penargetan perilaku, atau menghubungi anak.

## Apa yang Firebase tidak kumpulkan dari Tenara

Kami secara eksplisit menonaktifkan Advertising ID (AAID) dan Android ID (SSAID) pada tingkat platform. Tenara dikonfigurasi agar Firebase Analytics dan Firebase Crashlytics tidak mengumpulkan atau menggunakannya. Kami tidak memanggil setUserId, dan kami tidak menghubungkan data sesi Tenara apa pun dengan akun Google atau identitas lain. Firebase tidak menerima ID, judul, kanal, atau thumbnail video YouTube dari Tenara, dan tidak menerima rekaman suara, data wajah, atau pengukuran jarak.

## Mengapa kami mengumpulkan ini

Data pseudonim yang dijelaskan di atas membantu kami memahami apakah fitur berfungsi, di mana orang tua mengalami kebingungan, dan kerusakan mana yang perlu diperbaiki. Dasar hukum pemrosesan ini adalah kepentingan sah kami untuk memelihara dan meningkatkan aplikasi, yang konsisten dengan sifat data yang terbatas dan pseudonim.

## Berapa lama Firebase menyimpan data

Firebase Analytics menyimpan data peristiwa pseudonim hingga 14 bulan, yang saat ini merupakan default Google. Crashlytics menyimpan laporan kerusakan hingga 90 hari, yang saat ini merupakan default Crashlytics.

## Pemrosesan data lintas negara

Firebase disediakan oleh Google LLC, yang mengoperasikan infrastruktur global. Data Firebase dapat diproses di negara-negara di luar Indonesia, tunduk pada ketentuan dan perlindungan data Google yang berlaku. Praktik privasi Google untuk Firebase didokumentasikan di https://firebase.google.com/support/privacy.

## Server Tenara sendiri

Tenara tidak menjalankan server aplikasi yang menerima konten Anda. Internet digunakan oleh Tenara untuk pemutaran video YouTube melalui WebView, Google Play Billing untuk pembelian, pengambilan thumbnail video publik melalui endpoint oEmbed YouTube, dan unggahan analitik serta laporan kerusakan Firebase seperti yang dijelaskan di atas.

## Pembelian melalui Google Play

Pembelian diproses oleh Google Play. Google dapat memproses informasi akun, pembayaran, dan transaksi sesuai ketentuan dan kebijakan privasi Google Play. Tenara menerima status pembelian dan hak akses yang diperlukan untuk membuka akses. Tenara tidak menerima detail lengkap kartu pembayaran Anda atau informasi metode pembayaran lainnya yang disimpan oleh Google.

## Konten YouTube

Tenara memutar video YouTube yang Anda tambahkan, setujui, atau pilih dari sekumpulan kecil saran awal yang disediakan di dalam aplikasi untuk pengguna baru. Tenara tidak mengontrol, memoderasi, atau menjamin isi video YouTube. Video berasal dari YouTube dan tetap tunduk pada ketentuan, kebijakan, dan ketersediaan YouTube. Anda bertanggung jawab menentukan video mana yang sesuai untuk anak Anda. Jika Anda memiliki kekhawatiran tentang konten YouTube tertentu, silakan merujuk pada kebijakan YouTube.

Ketika video atau thumbnail YouTube dimuat, YouTube dan Google dapat menerima informasi permintaan normal yang diperlukan untuk menyediakan konten tersebut, seperti informasi perangkat, jaringan, dan permintaan pemutaran, sesuai kebijakan YouTube dan Google sendiri.

## Privasi anak

Tenara dirancang untuk orang tua dan pengasuh yang mendampingi waktu menonton anak kecil, terutama pada masa usia dini. Tenara dirancang sehingga pemasangan, pengaturan, pembelian, dan pengoperasian aplikasi dilakukan oleh orang tua atau pengasuh. Apabila persetujuan orang tua diwajibkan oleh hukum yang berlaku, orang tua atau pengasuh adalah pihak yang diharapkan memberikannya. Anak tidak mengoperasikan aplikasi, tidak membuat akun, dan tidak memasukkan informasi pribadi.

Pemrosesan kamera di perangkat terhadap anak selama sesi tayang adalah perkiraan jarak yang bersifat fungsional, bukan identifikasi, dan tidak menghasilkan data tersimpan tentang anak. Aktivitas aplikasi pseudonim yang terbatas dan dikumpulkan melalui Firebase tidak dihubungkan secara langsung oleh Tenara dengan identitas orang tua, anak, atau orang dewasa mana pun, dan digunakan hanya untuk pemeliharaan dan peningkatan aplikasi, tidak pernah untuk iklan atau pembuatan profil.

Jika Anda meyakini anak Anda telah memberikan informasi pribadi melalui Tenara, hubungi kami dan kami akan membantu.

## Kontak langsung dengan kami

Jika Anda mengirim email ke alamat dukungan kami, kami dapat menerima informasi apa pun yang Anda pilih untuk disertakan dalam pesan: alamat email Anda, isi pesan, tangkapan layar, dan rincian diagnostik apa pun yang Anda bagikan. Kami menggunakan informasi ini hanya untuk menanggapi Anda dan untuk meningkatkan aplikasi jika pesan Anda menunjukkan adanya bug atau masalah desain. Kami menyimpan korespondensi dukungan selama diperlukan untuk memberikan tanggapan tersebut, dan Anda dapat meminta kami menghapusnya.

## Keamanan

Kami menggunakan langkah-langkah teknis dan organisasional yang wajar untuk melindungi data yang diproses Tenara. Konten pribadi seperti rekaman suara dan pustaka Anda tetap berada di perangkat Anda. Pengenal iklan dinonaktifkan pada tingkat platform. Data analitik dan kerusakan melalui Firebase bersifat pseudonim dan tidak terhubung langsung dengan identitas Anda. Tidak ada aplikasi atau layanan internet yang dapat menjamin keamanan sempurna, tetapi kami berupaya menjaga apa yang ditangani Tenara tetap minimal dan terlindungi.

## Hak Anda di bawah UU PDP

UU Pelindungan Data Pribadi Indonesia memberikan Anda hak tertentu sebagai Subjek Data Pribadi. Anda memiliki hak atas informasi tentang bagaimana data Anda diproses, hak untuk mengakses dan memperoleh salinan data pribadi yang kami simpan tentang Anda, hak untuk memperbaiki ketidakakuratan, hak untuk meminta penghapusan, hak untuk menarik persetujuan apabila pemrosesan didasarkan pada persetujuan, hak untuk menolak pemrosesan, hak atas portabilitas data, dan hak untuk mengajukan pengaduan kepada otoritas pengawas.

Karena Tenara hanya mengumpulkan aktivitas aplikasi pseudonim yang terbatas dan tidak terhubung langsung dengan identitas Anda, dalam banyak kasus hanya sedikit data pribadi yang dapat kami akses untuk memenuhi permintaan tersebut. Untuk data pribadi apa pun yang mungkin kami simpan dari korespondensi langsung (misalnya pertukaran email dengan alamat dukungan kami), Anda dapat menggunakan hak-hak ini dengan menghubungi prelaunchsupport.tenara@gmail.com. Anda juga dapat mengajukan permintaan penghapusan data melalui formulir kami di https://docs.google.com/forms/d/e/1FAIpQLScuRnHY0RT6iloR7K42y7Y85DeFubnZ531W5JICN-KoNnEnJA/viewform. Kami akan menanggapi dalam jangka waktu yang diwajibkan oleh hukum yang berlaku, dan kami berupaya menanggapi dengan segera, umumnya dalam waktu 3 x 24 jam.

## Pilihan tentang pengumpulan data

Saat ini kami tidak menyediakan tombol terpisah di dalam aplikasi untuk menonaktifkan analitik dan pelaporan kerusakan. Data yang kami terima bersifat terbatas, pseudonim, dan digunakan hanya untuk pemeliharaan dan peningkatan aplikasi, bukan untuk iklan atau pembuatan profil pengguna individual. Anda dapat menghentikan pengumpulan lebih lanjut dengan menghapus aplikasi kapan saja. Jika Anda memiliki kekhawatiran khusus tentang pengumpulan data di Tenara, hubungi prelaunchsupport.tenara@gmail.com dan kami akan mendiskusikan situasi Anda.

## Data yang dibagikan dengan pihak ketiga

Kami tidak menjual data pribadi atau mengungkapkannya untuk tujuan iklan atau pemasaran. Kami menggunakan Firebase Analytics dan Firebase Crashlytics untuk memproses data terbatas yang dijelaskan di atas atas nama kami, mengikuti ketentuan Firebase dan dokumentasi privasi Google.

## Perubahan kebijakan ini

Jika kami mengubah kebijakan ini, versi yang diperbarui akan diposting di alamat ini dengan tanggal berlaku yang baru. Perubahan material akan ditandai di dalam aplikasi jika memungkinkan.

## Hukum yang berlaku dan bahasa

Kebijakan ini diatur oleh hukum Republik Indonesia. Setiap perselisihan yang timbul berdasarkan kebijakan ini tunduk pada yurisdiksi pengadilan Jakarta, Indonesia, kecuali hukum yang berlaku memberikan hak yang tidak dapat dikesampingkan untuk mengajukan klaim di tempat lain. Kebijakan ini diterbitkan dalam Bahasa Indonesia dan Bahasa Inggris. Apabila terdapat perbedaan antara kedua versi tersebut, versi Bahasa Indonesia yang berlaku.

## Kontak

PT Bitpoin Teknologi Cakrawala
Jl. CBD Blok J9 No. 1
Bintaro Jaya Sektor 9
Kota Tangerang Selatan, Banten 15229
Indonesia

Email: prelaunchsupport.tenara@gmail.com
