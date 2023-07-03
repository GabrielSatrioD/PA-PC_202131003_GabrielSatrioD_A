Teori yang mendukung mengenai projek terkait :

Deteksi tepi merupakan metode yang telah banyak diimplementasikan dalam 
berbagai penelitian dan pada aspek yang bermacam-macam. 
Terdapat banyak jenis algoritma deteksi tepi, seperti Canny, Sobel, Prewitt, 
Robert, dan Laplacian of Gaussian (LoG). Setiap algoritma deteksi tepi memiliki 
kelebihan dan kekurangan masing-masing. Algoritma Sobel memiliki kelebihan 
yaitu peka terhadap garis diagonal dibanding garis horizontal dan vertikal, 
sebalikanya algoritma Prewitt lebih peka terhadap garis horizontal dan vertikal 
daripada garis diagonal. Diantara semua algoritma deteksi 
tepi yang ada, Canny merupakan algoritma deteksi tepi memberikan hasil yang 
paling optimal untuk digunakan pada hampir segala macam kondisi. Hal tersebut dikarenakan algoritma Canny dapat 
memberikan garis hasil deteksi tepi yang tipis dengan ketebalan 1 piksel sehingga 
dapat dinyatakan paling akurat dibandingkan algoritma deteksi tepi yang lain 

Berikut adalah tahapan rinci untuk menyelesaikan proyek tentang deteksi garis:

Pemahaman Masalah:

Pelajari secara menyeluruh tentang deteksi garis, termasuk konsep dan metode yang terkait.
Pahami kebutuhan spesifik proyek, seperti jenis garis yang akan dideteksi, lingkungan aplikasi, dan tujuan akhir proyek.

Penyusunan Rencana:

Tentukan algoritma dan metode deteksi garis yang akan digunakan. Beberapa metode yang umum digunakan adalah Transformasi Hough, Canny Edge Detection, dan Segmentasi Berbasis Warna.
Identifikasi alat dan sumber daya yang diperlukan, seperti bahasa pemrograman, perpustakaan atau framework, dataset, dan perangkat keras (jika diperlukan).

Pengumpulan Dataset:

Kumpulkan dataset yang berisi gambar dengan garis yang akan dideteksi.
Pastikan dataset mencakup berbagai situasi, sudut pandang, pencahayaan, dan variasi lainnya yang mungkin terjadi dalam penggunaan sehari-hari.
Pra-Pemrosesan Data:

Lakukan pra-pemrosesan data pada dataset, seperti penghilangan noise, peningkatan kontras, dan normalisasi gambar.
Jika perlu, lakukan segmentasi gambar untuk memisahkan objek utama (garis) dari latar belakang.

Implementasi Algoritma Deteksi Garis:

Mulailah mengimplementasikan algoritma deteksi garis yang telah dipilih.
Gunakan perpustakaan atau framework yang sesuai untuk mempercepat dan menyederhanakan proses implementasi.
Pelatihan Model:

Jika Anda menggunakan pendekatan berbasis pembelajaran mesin, latih model dengan dataset yang sudah dikumpulkan.
Bagi dataset menjadi set pelatihan dan set validasi, dan gunakan teknik seperti validasi silang atau bootstrap jika diperlukan.
Atur parameter dan hiperparameter model untuk meningkatkan performa deteksi garis.

Evaluasi Model:

Evaluasi model yang telah dilatih menggunakan metrik yang sesuai, seperti akurasi, presisi, recall, atau F1-score.
Analisis hasil evaluasi dan identifikasi kemungkinan penyebab kesalahan atau keterbatasan model.
Validasi dan Penyetelan:

Validasi model menggunakan dataset uji yang independen dari dataset pelatihan dan validasi.
Lakukan penyetelan tambahan pada model untuk memperbaiki performa jika diperlukan.

Integrasi dan Uji Coba:

Integrasikan model deteksi garis ke dalam aplikasi atau sistem yang relevan.
Lakukan uji coba pada berbagai situasi dan kondisi untuk memverifikasi keandalan dan kinerja model.

Pemeliharaan dan Peningkatan:

Terus monitor dan perbarui model deteksi garis jika diperlukan.
Tinjau kembali performa model secara berkala dan perbarui metode atau algoritma jika ada inovasi baru.
