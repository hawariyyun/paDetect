# paDetect: Aplikasi Skrining dan Deteksi Panik Peserta Vaksin untuk Meningkatkan Efisiensi Antrian
## Backgrounder
Berdasarkan peneliitian yang dilakukan oleh Nikmatillahi dkk. (2021) pelayanan vaksinasi COVID-19 yang pada awalnya 4 meja membuat sebanyak 80% penerima vaksin harus menunggu terlalu lama [1]. Oleh karena itu, per tanggal 05 Mei 2021 Kementerian Kesehatan melakukan penyederhanaan layanan menjadi 2 meja meliputi skrining dan penyuntikan vaksin. Akan tetapi, pada lansia dan ibu hamil masih banyak yang tidak lolos uji skrining. Pemerintah Kabupaten Wonogiri mencatat bahwa per tanggal 6 Oktober 2021 banyak lansia yang tidak lolos uji skrining sehingga tingkat vaksiniasi lansia tidak mencapai 60%. Kasus yang serupa juga terjadi di daerah lain dan pada ibu hamil. Proses skrining vaksin yang hanya dapat dilakukan di lokasi penyuntikan membuat efektivitas vaksinasi menurun. Pada proyek ini, kami membuat *website* untuk skrining peserta yang akan melakukan vaksinasi.

Aplikasi paDetect mencakup form skrining, deteksi panik, dan *Frequently Asked Question* (FAQ). *Form* skrining yang terdapat di dalam aplikasi memuat pertanyaan-pertanyaan yang bersumber dari Kementerian Kesehatan [2]. Proses pengambilan keputusan dilakukan oleh *library* streamlit dengan 3 jenis keputusan yaitu lanjut vaksin, ditunda, atau tidak bisa menerima vaksin. Selain itu, paDetect memiliki fitur tambahan untuk mendeteksi apakah peserta vaksin sedang panik atau tidak yang diperoleh dari algoritma *machine learning*. Adanya aplikasi ini diharapkan menjadi inovasi untuk meningkatkan laju vaksinasi Indonesia.

Pengerjaan proyek dilakukan selama 5 minggu yang meliputi:
1. Pencarian dataset deteksi ekspresi wajah 
2. Pembuatan model algortima deteksi ekspresi wajah
3. Pembuatan front-end dan integrasi model
4. *Deployment* sistem dan penyusunan project brief
5. Pembuatan powerpoint dan video presentasi


## Deployed Link
[paDetect COVID-19 Vaccination Screening App](https://vacscreenpd.herokuapp.com/)

## Other Resources Link:

### Library or external repository/API used:
[1] [Streamlit](https://streamlit.io/)

### Dataset Link:
[1] [FER-2013](https://www.kaggle.com/msambare/fer2013)

### Academic Paper Link
[1] [Optimalisasi Alur Pelayanan Vaksinasi Covid-19 di RSU X Kota Bandung Tahun 2021](https://jurnal.healthsains.co.id/index.php/jhs/article/view/214)

### References Link:
[1] [Banyak yang gagal Skrining, Vaksinasi Covid-19 Lansia di Wonogiri Baru 50 Persen](https://regional.kompas.com/read/2021/10/07/093102078/banyak-yang-gagal-skrining-vaksinasi-covid-19-lansia-di-wonogiri-baru-50?page=all)
[2] [Keputusan Menteri Kesehatan Republik Indonesia No. HK 01.07/MENKES/4638/2021](https://persi.or.id/wp-content/uploads/2021/07/KMK-4638-2021.pdf)
