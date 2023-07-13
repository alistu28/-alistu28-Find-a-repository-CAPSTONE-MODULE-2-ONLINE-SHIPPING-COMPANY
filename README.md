# Online Shipping Company

_Created By : Alifia Listu Samatha - JCDS Purwadhika Bandung_

Dalam proyek ini, saya akan memposisikan diri saya sebagai data analis di sebuah perusahaan. Berdasarkan data yang diperoleh, saya akan membuat serangkaian pertanyaan berdasarkan kebutuhan bisnis dan masalah yang mungkin dihadapi perusahaan terkait.

Saya akan menjawab pertanyaan yang diajukan oleh perusahaan, membuat cerita dan visualisasi, serta menyajikan _insight_ dari analisis yang dapat digunakan sebagai pemangku kepentingan untuk membuat keputusan bisnis.

Tableau Story Link : [Disini](https://public.tableau.com/app/profile/alifia.listu.samatha/viz/OnlineRetailShipping/Story1?publish=yes)

## Latar Belakang

Perusahaan E-Commerce Internasional di bidang elektronik bekerja sama dengan data analyst untuk menganalisa data pengiriman produk pelanggan, dimana dari banyak data pengiriman produk, beberapa pengiriman tidak tiba tepat waktu atau tertunda, sehingga banyak pelanggan yang memberikan peringkat rendah kepada perusahaan. Hal ini akan berdampak buruk untuk reputasi perusahaan yang dapat mengakibatkan pelanggan tidak percaya lagi dengan perusahaan dan perusahaan akan mengalami kebangkrutan.

## Pernyataan Masalah

Perusahaan ingin mengetahui apakah produk yang dibeli pelanggan sampai kepada pelanggan tepat waktu atau tidak. Analisis ini nantinya dapat membantu perusahaan untuk menentukan langkah yang harus dilakukan untuk memecahkan masalah.

Berikut ini adalah pertanyaan yang akan dijawab dalam analis dibawah ini:
1. Apakah produk sampai tepat waktu?
2. Apa yang harus dilakukan untuk meningkatkan kemungkinan produk sampai tepat waktu?
3. Apakah penilaian pelanggan sudah bagus?
4. Apa yang harus dilakukan untuk meningkatkan penilaian pelanggan?

## Kesimpulan

1. Sebanyak 59.67% produk datang terlambat dan 40.33% produk datang tepat waktu.
2. Produk yang jumlah kedatangan tepat waktunya lebih tinggi  adalah produk dengan beban berat dan produk dengan diskon dibawah 13%. 
3. Produk terlalu menumpuk di satu Warehouse saja.
4. Klasifikasi parameter kepentingan/urgensi produk tidak jelas berdasarkan apa.
5. Perusahaan lebih memprioritaskan barang dengan harga tinggi dibandingkan dengan yang kepetingan/urgensinya tinggi.
6. Mode pengiriman juga terlalu berfokus pada satu mode, yaitu dengan kapal karena lebih murah.
7. Mode pengiriman pesawat mengalami presentase keterlambatan yang lebih banyak dibandingkan dengan mode lain. Disusul kedua oleh mode kapal dengan perbedaan sekitar 0.4%.
8. Produk yang mahal justru lebih banyak memakai mode pengiriman jalur darat. Hal ini membuat mode darat memiliki presentase tepat waktu lebih tinggi dibandingkan yang lainnya.
9. Pelanggan dengan member golden membeli lebih banyak produk mahal, namun justru yang memberikan presentase rating tinggi terbanyak adalah pelanggan dengan member platinum.
10. Customer rating sebenarnya tidak berkorelasi dengan semua kolom. Namun ada sedikit korelasi menuju 0 yang dapat dipertimbangkan, yaitu banyaknya perusahaan menerima call, pelanggan yang memiliki member platinum, dan harga produk yang mahal mempengaruhi kenaikan rating.

## Rekomendasi

1. Jika perusahaan tidak bisa memastikan pengiriman tepat waktu, perusahaan tidak usah memberikan diskon diatas 13%. Fokus ke perihal lain selain diskon.
2. Sebarlah produk di berbagai gudang, jangan hanya menumpuk di satu gudang saja. Akan berdampak pada antrian pengiriman.
3. Memperbaiki kebijakan terkait *product importance* karena masih belum jelas.
4. Kami merekomendasikan beberapa alternatif terkait kebijakan pemilihan *product importance*:
   1. Diukur dari Harga Barang. Jika barang mahal dikategorikan sebagai produk penting (*high importance*), dan perusahaan fokus dalam menangani produk tersebut, tingkat kepercayaan pelanggan akan semakin meningkat, rating juga akan meningkat.
   2. Diukur dari Destinasi Pengiriman. Produk dikategorikan berdasarkan destinasi pengiriman domestik maupun internasional. Jika pengiriman destinasinya internasional, produk bisa lebih diprioritaskan karena butuh waktu lebih lama unutk pengiriman.
   3. Diukur dari Opsi Pengiriman. Produk dikategorikan berdasarkan opsi pengiriman berbayar atau gratis ongkir. Jika memang berbayar bisa lebih diprioritaskan. Jika pengiriman gratis ongkir, pelanggan harus diberikan durasi waktu yang ditentukan untuk pengiriman produk mereka untuk menghindari pelanggan menelepon (*customer care call*) untuk menanyakan tentang pengiriman.
5. Pertahankan untuk sering menjawab *customer care calls*, *chance* rating tinggi semakin besar, walaupun barangnya sampai tidak tepat waktu.
6. Menjaga ketepatan waktu delivery kepada existing customers (golden dan platinum), karena merekalah yang berpeluang besar memberikan rating tinggi.
