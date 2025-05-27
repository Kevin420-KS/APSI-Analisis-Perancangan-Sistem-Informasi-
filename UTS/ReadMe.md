Alur Sistem Pembayaran Makanan Food Court Mall

1. Pembeli membuka aplikasi/sistem dan melihat menu makanan yang tersedia di food court.

2. Pembeli memilih makanan yang ingin dibeli dari daftar menu.

3. Pembeli memilih metode pembayaran:
•	E-money (biasa atau PayLater)
•	Kartu Debit
•	Kartu Kredit
•	Cash

4. Sistem memproses pembayaran:
•	Jika metode adalah Kartu Debit, Kartu Kredit, atau E-money PayLater:
o	Sistem mengirimkan permintaan validasi ke pihak bank.
o	Bank memeriksa dan mengirimkan status validasi pembayaran.
o	Jika pembayaran valid dan menggunakan Kartu Kredit atau PayLater, sistem menambahkan bunga.
o	Pesanan ditandai sebagai Express Order (makanan akan diantar lebih cepat).
•	Jika metode adalah Cash atau E-money biasa (tanpa PayLater):
o	Sistem tidak melakukan validasi bank.
o	Pesanan ditandai sebagai Standard Order (makanan diantar sedikit lebih lama).
o	Tidak ada bunga yang dikenakan.

5. Sistem menyimpan transaksi dan mengirimkan instruksi pengantaran ke pelayan.

6. Pelayan menerima instruksi dan mengantar makanan ke meja pembeli sesuai prioritas (express atau standar).

7. Saat mengantar, pelayan menyebutkan nama pesanan dan nomor meja agar pembeli dapat mengenali pesanannya.

8. Pembeli menerima makanan, dan transaksi selesai.