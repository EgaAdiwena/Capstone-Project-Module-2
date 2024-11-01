# **Capstone 2 Purwadhika**

Sebagai bagian dari tugas akhir program Data Science Purwadhika, notebook ini disusun untuk mengimplementasikan keterampilan analisis data. Dalam proyek ini, saya bersimulasi sebagai analis data yang ditugaskan untuk menggali *insights* dari dataset yang disediakan, dengan tujuan menjawab pertanyaan-pertanyaan bisnis yang relevan.

by : Ega Adiwena

# **Amazon Web Services SaaS Sales**

Amazon Web Services (AWS) adalah platform komputasi cloud yang menyediakan berbagai layanan, seperti penyimpanan database, daya komputasi, dan layanan pengiriman konten. AWS menawarkan lebih dari 200 layanan yang dapat diakses dari pusat data di seluruh dunia.

Software as a Service (SaaS) di AWS merupakan model penyediaan aplikasi berbasis cloud. Vendor SaaS seperti AWS mengelola seluruh infrastruktur, sehingga pelanggan hanya perlu berfokus pada penggunaan aplikasi. Model pembayarannya pun fleksibel, biasanya berbasis langganan. Amazon WorkDocs adalah salah satu contohnya, memungkinkan kolaborasi dokumen secara real-time di cloud.

# **Permasalahan dan Tujuan**

**Permasalahan :**

1.   Seperti apa distribusi pelanggan SaaS?
2.   Bagaimana tren penjualan sepanjang 2020-2023?
3.   Seperti apa performa penjualan produk SaaS?

**Tujuan :**

1.   Implementasi strategi penetrasi pasar yang terukur
2.   Evaluasi produk guna memaksimalkan pendapatan dan profitabilitas
3.   Penentuan strategi penjualan yang paling efektif

Untuk menjawab permasalahan dan mengimplementasi tujuan yang didapat, saya mendeterminasi divisi *product development* dan *sales marketing* sebagai *stakeholder*.

# **Overview Data**

1.   Pengecekan data *missing* dan *duplicate*
2.   Perubahan format tanggal
3.   Pengecekan data *outlier*
4.   Pengecekan distribusi data

# **Hasil Analisis**

**Analisis Segmentasi Penjualan**

1.   Kontribusi penjualan terbesar berasal dari `United States`, sementara penjualan di `Qatar` masih memiliki potensi untuk ditingkatkan.
2.   Sektor industri `Finance` merupakan kontributor utama dalam pembelian produk SaaS, sementara industri lainnya atau `Misc` dan `Transportation` memerlukan penyesuaian strategi penjualan yang lebih efektif.
3.   Segmen *Small Medium Business* atau `SMB` menjadi pendorong utama pendapatan produk SaaS, sementara segmen perusahaan besar atau `Enterprise` masih menjadi tantangan dalam upaya meningkatkan penjualan.
4.   Berdasarkan data penjualan, Nyonya `Diane Murray` dari Jerman berhasil meraih posisi puncak sebagai pelanggan dengan kontribusi pembelian terbesar.

**Analisis Penjualan Produk**

1.   Analisis data penjualan menunjukkan peningkatan signifikan pada produk SaaS dari tahun 2020 hingga 2023. Tren musiman yang terlihat, dengan puncak penjualan di kuartal ketiga dan penurunan di kuartal pertama, mengindikasikan pengaruh siklus anggaran tahunan perusahaan.
2.   Produk `ContactMatcher` mendominasi pangsa pasar produk SaaS, sementara produk `Alchemy` menunjukkan kinerja penjualan yang kurang memuaskan dibandingkan produk lainnya.
3.   Meskipun volume kuantitas penjualan produk `Storage` cukup signifikan, namun produk ini memiliki total pendapatan terkecil di antara produk SaaS lainnya.

**Analisis Profit**

1.   Produk `Alchemy` merupakan produk unggulan. Strategi pemasaran yang diterapkan pada produk `Alchemy` terbukti sangat efektif, terbukti dari kontribusi terbesarnya terhadap total keuntungan perusahaan.
2.   Produk `Marketing Suite` mengalami kendala. Kebijakan pemberian diskon yang terlalu agresif menjadi penyebab utama defisit penjualan pada produk `Marketing Suite`. Kebijakan ini dinilai tidak efektif dan justru merugikan perusahaan.

**Analisis Korelasi**

1.   Hubungan yang kuat antara `Sales` dan `Profit` menunjukkan bahwa peningkatan penjualan adalah salah satu cara efektif untuk meningkatkan profitabilitas perusahaan.
2.   Adanya hubungan negatif antara pemberian `Discount` dan `Profit` perusahaan. Semakin besar diskon yang diberikan, semakin kecil keuntungan yang diperoleh.
3.   Tidak ada hubungan yang signifikan antara pemberian `Discount` dan peningkatan `Sales`. Artinya, saat perusahaan memberikan diskon, penjualan tidak selalu meningkat secara signifikan

# **Rekomendasi**

**Penyesuaian Produk untuk Penetrasi Global**

Agar produk atau layanan diterima dengan baik di negara dengan perkembangan teknologi yang berbeda, kita perlu menyesuaikan produk dengan kondisi lokal. Dengan memastikan kualitas dan relevansi produk pada negara tujuan, kita dapat memaksimalkan peluang keberhasilan dan mendapatkan kepercayaan pelanggan di pasar internasional.

**Penerapan Program Loyalty Benefit dan Referal**

Melalui program loyalitas, kita ingin membangun hubungan jangka panjang dengan pelanggan. Dengan memberikan penghargaan yang sesuai, kita berharap pelanggan akan merasa lebih terikat dengan merek kita dan enggan beralih ke kompetitor.

Program referal dapat mendorong pelanggan yang puas untuk merekomendasikan bisnis kita kepada orang lain dengan menawarkan hadiah sebagai imbalan. Dengan cara ini, pelanggan yang puas dapat menjadi promotor merek. Program referal juga dapat digunakan untuk menarik pengguna baru dengan menawarkan insentif yang menarik.

**Evaluasi Harga Produk**

Perlu dilakukan analisis mendalam terhadap harga produk Saas, khususnya produk `Storage`, untuk menemukan titik harga optimal guna dapat meningkatkan pendapatan.

**Evaluasi Pemberian Diskon**

Sebagai upaya untuk menjaga stabilitas harga, pemberian diskon akan diberikan secara selektif kepada pelanggan yang melakukan pembayaran penuh di muka untuk pembelian dalam jumlah besar.

**Alokasi Dana untuk Pengembangan Produk**

Diperlukan alokasi anggaran khusus untuk pengembangan produk dan kegiatan pemasaran, terutama untuk produk dengan volume penjualan yang rendah seperti `Alchemy` dan `Big Ol Database`.
