Meningkatkan Efisiensi Pemasaran Bank DKK dengan Machine Learning: Sebuah Perjalanan Data

Bayangkan Anda adalah bagian dari tim pemasaran Bank DKK, sebuah institusi keuangan yang berjuang untuk menarik nasabah baru ke produk deposito berjangka melalui kampanye telepon. Setiap hari, tim menghabiskan waktu dan anggaran untuk menghubungi ribuan pelanggan, hanya untuk mendapatkan tingkat konversi yang rendah. Biaya melonjak, produktivitas terhambat, dan hasilnya tidak sebanding dengan usaha. Terdengar familiar? Tantangan inilah yang menginspirasi saya, Derin Adimar, untuk mengembangkan solusi berbasis data dalam Capstone Modul III (JCDS 0610)—sebuah proyek yang tidak hanya mengatasi masalah bisnis nyata, tetapi juga menunjukkan kekuatan machine learning dalam mengubah strategi pemasaran.

Tantangan: Kampanye yang Mahal dan Tidak Efisien

Bank DKK beroperasi di pasar keuangan yang kompetitif, di mana deposito berjangka adalah produk kunci untuk pertumbuhan. Namun, pendekatan pemasaran mereka saat ini—kampanye telepon massal—menghadapi tiga masalah besar:





Biaya Tinggi: Sebagian besar anggaran terbuang untuk menghubungi pelanggan yang tidak berminat.



Konversi Rendah: Hanya sebagian kecil pelanggan yang menerima penawaran deposito.



Produktivitas Terhambat: Tim pemasaran kewalahan dengan panggilan tidak produktif, mengurangi fokus pada prospek potensial.

Tantangan ini mendorong pertanyaan: Bagaimana Bank DKK bisa menargetkan pelanggan yang tepat, mengurangi biaya, dan meningkatkan konversi? Jawabannya terletak pada data—dan kekuatan machine learning untuk mengungkap pola tersembunyi.

Solusi: Model Prediktif untuk Targeting Cerdas

Dengan dataset historis kampanye Bank DKK, yang mencakup demografi pelanggan (usia, pekerjaan), status finansial (saldo, pinjaman), dan metrik interaksi (frekuensi kontak, hasil kampanye sebelumnya), saya membangun model prediktif untuk mengidentifikasi pelanggan dengan probabilitas tertinggi untuk berlangganan deposito. Proyek ini bukan sekadar latihan teknis; ini adalah upaya untuk memberikan solusi yang actionable bagi Chief Marketing Officer (CMO) Bank DKK, yang ingin mengoptimalkan sumber daya dan mencapai hasil nyata.

Langkah-Langkah Perjalanan





Exploratory Data Analysis (EDA): Saya menyelami data untuk memahami pola. Misalnya, pelanggan dengan riwayat kampanye sukses (poutcome = success) cenderung lebih responsif, sementara kontak berlebihan justru menimbulkan kejenuhan.



Preprocessing Data: Menangani ketidakseimbangan kelas dengan teknik oversampling, mengencode variabel kategorikal, dan menskalakan fitur numerik untuk memastikan model bekerja optimal.



Pemodelan Machine Learning: Saya menguji beberapa algoritma—Logistic Regression, Random Forest, dan Gradient Boosting—dengan Gradient Boosting sebagai pemenang berkat performanya yang kuat.



Evaluasi dan Tuning: Model diukur dengan metrik seperti AUC (0.76), Precision (0.69), Recall (0.82), dan F2 Score (0.79), yang menunjukkan kemampuan model untuk menyeimbangkan deteksi pelanggan potensial dan meminimalkan kesalahan.



Rekomendasi Bisnis: Berdasarkan wawasan, saya menyusun strategi untuk segmentasi pelanggan, personalisasi kampanye, dan optimasi saluran komunikasi.

Teknologi di Balik Layar

Proyek ini dibangun dengan Python dan berbagai library canggih:





Data Processing: pandas, numpy



Visualisasi: seaborn, matplotlib, plotly



Machine Learning: scikit-learn, xgboost, lightgbm, imblearn



Preprocessing: category_encoders, jcopml

Semua analisis dilakukan dalam Jupyter Notebook, dengan model terbaik disimpan dalam format .pkl untuk keperluan deployment.

Hasil: Dampak Nyata untuk Bank DKK

Model Gradient Boosting yang dihasilkan menunjukkan performa luar biasa:





AUC 0.76: Model dapat membedakan pelanggan potensial dengan andal.



Recall 0.82: Kemampuan tinggi untuk menangkap pelanggan yang benar-benar akan berlangganan.



F2 Score 0.79: Keseimbangan optimal untuk data tidak seimbang, memastikan hasil yang relevan untuk bisnis.

Wawasan kunci dari analisis:





Riwayat Kampanye Sukses adalah prediktor utama konversi.



Usia 30–50 tahun dan pekerjaan stabil (misalnya, profesional) adalah segmen potensial.



Kontak berlebihan dapat mengurangi minat pelanggan, menunjukkan perlunya pendekatan yang lebih terarah.

Dengan model ini, Bank DKK dapat:





Mengurangi biaya hingga 30% dengan menghindari kontak tidak efektif.



Meningkatkan konversi melalui targeting yang lebih cerdas.



Meningkatkan produktivitas tim dengan fokus pada prospek berkualitas tinggi.

Rekomendasi: Strategi untuk Masa Depan

Berdasarkan temuan, saya merekomendasikan langkah-langkah berikut untuk Bank DKK:





Segmentasi Cerdas: Prioritaskan pelanggan dengan riwayat kampanye sukses, saldo sehat, dan usia produktif.



Hindari Kejenuhan: Batasi frekuensi kontak dan fokus pada kualitas interaksi.



Personalisasi Pesan: Sesuaikan penawaran berdasarkan demografi dan status finansial pelanggan.



Retargeting Efektif: Alokasikan sumber daya untuk pelanggan dengan riwayat positif.



Optimasi Saluran: Eksplorasi kanal digital untuk menjangkau pelanggan muda.



Integrasi Model: Gunakan model sebagai alat rekomendasi untuk tim pemasaran, dengan pembaruan berkala untuk menjaga akurasi.
