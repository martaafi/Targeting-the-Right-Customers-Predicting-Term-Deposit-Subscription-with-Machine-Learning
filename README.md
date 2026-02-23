# Targeting the Right Customers: Predicting Term Deposit Subscription with Machine Learning
## Latar Belakang
Dalam industri perbankan, memahami perilaku nasabah sangat krusial untuk meningkatkan efektivitas kampanye pemasaran. Salah satu tantangan terbesar adalah mengetahui siapa saja yang berpotensi merespons positif terhadap penawaran produk keuangan tertentu, seperti deposito berjangka. Dengan memanfaatkan data historis yang mencakup informasi demografis nasabah, riwayat interaksi, serta hasil kampanye  sebelumnya, proyek ini akan membangun model klasifikasi yang mampu memprediksi secara akurat kemungkinan seorang  nasabah untuk membeli produk deposito.

## Tujuan
Membuat model machine learning yang dapat mengklasifikasikan nasabah ke dalam dua kategori:
- 1: nasabah diprediksi akan membeli deposito berjangka
- 0: nasabah diprediksi tidak akan membeli

## Dataset
| Nama Kolom | Deskripsi |
| ---------- | --------- |
| customer_number | Angka unik yang diberikan kepada setiap nasabah untuk membedakan satu nasabah dengan yang lainnya |
| usia | Usia nasabah (dalam tahun) |
| pekerjaan | Jenis pekerjaan nasabah |
| status_perkawinan | Status perkawinan nasabah (termasuk duda/janda sebagai "cerai") |
| pendidikan | Tingkat pendidikan terakhir yang diselesaikan oleh nasabah |
| gagal_bayar_sebelumnya | Apakah nasabah pernah mengalami gagal bayar kredit sebelumnya |
| pinjaman_rumah | Apakah nasabah memiliki pinjaman rumah |
| pinjaman_pribadi | Apakah nasabah memiliki pinjaman pribadi |
| jenis_kontak | Jenis media komunikasi yang digunakan untuk menghubungi nasabah |
| bulan_kontak_terakhir | Bulan ketika nasabah terakhir kali dihubungi |
| hari_kontak_terakhir | Hari dalam seminggu ketika nasabah terakhir kali dihubungi |
| durasi_kontak | Durasi kontak terakhir dalam satuan detik (tidak digunakan dalam model prediksi nyata karena hanya diketahui setelah kontak dilakukan) |
| jumlah_kontak_kampanye_ini | Jumlah total kontak yang dilakukan selama kampanye saat ini |
| hari_sejak_kontak_sebelumnya | Jumlah hari sejak nasabah terakhir dihubungi dari kampanye sebelumnya (999 berarti belum pernah dihubungi sebelumnya) |
| jumlah_kontak_sebelumnya | Jumlah kontak yang dilakukan sebelum kampanye saat ini terhadap nasabah |
| hasil_kampanye_sebelumnya | Hasil dari kampanye pemasaran sebelumnya terhadap nasabah |
| tingkat_variasi_pekerjaan | Indikator variasi tingkat pekerjaan secara kuartalan |
| indeks_harga_konsumen | Indeks harga konsumen pada bulan terkait |
| indeks_kepercayaan_konsumen | Indeks tingkat kepercayaan konsumen pada bulan terkait |
| suku_bunga_euribor_3bln | Suku bunga Euribor untuk tenor 3 bulan |
| jumlah_pekerja | Jumlah total tenaga kerja dalam indikator kuartalan |
| berlangganan_deposito | Apakah nasabah memutuskan untuk berlangganan produk deposito berjangka (1 berarti berlangganan deposito dan 0 berarti customer tidak berlangganan deposito) |

## Hasil
Model terbaik dalam proyek ini berhasil memperoleh akurasi sebesar 0,8979 (89,79%) dengan AUC Score sebesar 0,7989 (79,89%)

