# Python - Data Analyst

Final Project Python for Data Analyst

Berikut dataset yang akan digunakan:
1. order_detail
2. sku_detail
3. customer_detail
4. payment_detail

Mengenai penjelasan dataset adalah sebagai berikut:
order_detail:
   1. id               : angka unik dari order / id_order
   2. customer_id      : angka unik dari pelanggan
   3. order_date       : tanggal saat dilakukan transaksi
   4. sku_id           : angka unik dari produk (sku adalah stock keeping unit)
   5. price            : harga yang tertera pada tagging harga
   6. qty_ordered      : jumlah barang yang dibeli oleh pelanggan
   7. before_discount  : nilai harga total dari produk (price * qty_ordered)
   8. discount_amount  : nilai diskon product total
   9. after_discount   : nilai harga total produk ketika sudah dikurangi dengan diskon
   10. is_gross        : menunjukkan pelanggan belum membayar pesanan
   11. is_valid        : menunjukkan pelanggan sudah melakukan pembayaran
   12. is_net          : menunjukkan transaksi sudah selesai
   13. payment_id      : angka unik dari metode pembayaran
 
sku_detail:
   1. id               : angka unik dari produk (dapat digunakan untuk key saat join)
   2. sku_name         : nama dari produk
   3. base_price       : harga barang yang tertera pada tagging harga / price
   4. cogs             : cost of goods sold / total biaya untuk menjual 1 produk
   5. category         : kategori produk

customer_detail:
   1. id               : angka unik dari pelanggan
   2. registered_date  : tanggal pelanggan mulai mendaftarkan diri sebagai anggota

Payment_detail:
   1. id               : angka unik dari metode pembayaran
   2. payment_method   : metode pembayaran yang digunakan

Pertanyaan:
   1. Dear Data Analyst,
      
      Akhir tahun ini, perusahaan akan memberikan hadiah bagi pelanggan yang memenangkan kompetisi Festival Akhir Tahun. Tim Marketing membutuhkan bantuan untuk menentukan perkiraan hadiah yang akan diberikan pada pemenang kompetisi nantinya. Hadiah tersebut akan diambil dari TOP 5 Produk dari Kategori Mobiles & Tablets selama tahun 2022, dengan jumlah kuantitas penjualan (valid = 1) paling tinggi.
      
      Mohon bantuan, untuk mengirimkan data tersebut sebelum akhir bulan ini ke Tim Marketing. Atas bantuan yang diberikan, kami mengucapkan terima kasih.

      Regards

      Tim Marketing
      
   2. Dear Data Analyst,

      Menindaklanjuti meeting gabungan Tim Werehouse dan Tim Marketing, kami menemukan bahwa ketersediaan stock produk dengan Kategori Others pada akhir 2022 kemarin masih banyak.

      A. Kami mohon bantuan untuk melakukan pengecekan data penjualan kategori tersebut dengan tahun 2021 secara kuantitas penjualan. Dugaan sementara kami, telah terjadi penurunan kuantitas penjualan pada 2022 dibandingkan 2021. (Mohon juga menampilkan data ke-15 kategori)
      B. Apabila memang terjadi penurunan kuantitas penjualan pada kategori Others, kami mohon bantuan untuk menyediakan data TOP 20 nama produk yang mengalami penurunan paling tinggi pada 2022 jika dibanding dengan 2021. Hal ini kami gunakan sebagai bahan diskusi pada meeting selanjutnya.

      Mohon bantuan untuk mengirimkan data tersebut paling lambat 4 hari dari hari ini. Atas bantuan yang diberikan, kami mengucapkan terima kasih.

      Regards

      Tim Werehouse
      
   4. Dear Data Analyst,

      Terkait ulang tahun perusahaan pada 2 bulan mendatang, Tim Digital Marketing akan memberikan informasi promo bagi pelanggan pada akhir bulan ini. Kriteria pelanggan yang akan kami butuhkan adalah mereka yang sudah melakukan check-out namun belum melakukan pembayaran (is_gross = 1) selama tahun 2022. Data yang kami butuhkan adalah ID Customer dan Registered Date.

      Mohon bantuan, untuk mengirimkan data tersebut sebelum akhir bulan ini ke Tim Digital Marketing. Atas bantuan yang diberikan, kami mengucapkan terima kasih.

      Regards

      Tim Digital Marketing
      
   5. Dear Data Analyst,

      Pada bulan October hingga Desember 2022, kami melakukan campaign setiap hari Sabtu dan Minggu. Kami hendak menilai, apakah campaign tersebut cukup berdampak pada kenaikan penjualan (before_discount). Mohon bantuan untuk menampilkan data:

      A. Rata-rata harian penjualan weekends (Sabtu dan Minggu) vs rata-rata harian penjualan weekdays (Senin-Jumat) per bulan tersebut. Apakah ada peningkatan penjualan pada masing-masing bulan tersebut.
      B. Rata-rata harian penjualan weekends (Sabtu dan Minggu) vs rata-rata harian penjualan weekdays (Senin-Jumat) keseluruhan 3 bulan tersebut.

      Mohon bantuan untuk mengirimkan data tersebut paling lambat minggu depan. Atas bantuan yang diberikan, kami mengucapkan terima kasih.

      Regards

      Tim Campaign

