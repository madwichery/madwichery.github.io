
# **Research projects:**
## Skripsi (2022) 
### Klasifikasi Ayat Al-Qur'an dengan Mel Frequency Cepstral Coefficient (MFCC) dan Artificial Neural Network (ANN)
- Mengidentifikasi suara Al-Qur'an yang dibacakan sesuai dengan surat dan ayatnya. 
- Menggunakan skema **MLOps** (Machine Learning Operations) dengan library **Weight and Biases** (WANDB).
- Data diupload di Artifact Wandb, dipreprocessing ke MFCC kemudian diklasifikasikan dengan ANN.
dengan flow:
  1. [Data yang digunakan diupload ke *Artifact* Weights & Biases](https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran-EDA/artifacts/dataset/raw-dataset/v0/files)
  2. [Explanatory Data Analysis (**EDA**): Data audio memiliki variabilitas **panjang yang berbeda-beda** tiap ayat.](https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran-EDA/reports/Exploratory-Data-Analysis-Skripsi-Menghadapi-Variabilitas-Durasi-Audio-dalam-Tugas-Klasifikasi--VmlldzozODI2NzUx) 
  3. [Preprocessing data audio untuk proses training menjadi **MFCC**](https://gist.github.com/madwichery/e41b08507672980d9b694b3e7c612ba8)
  4. [Training dengan **ANN**](https://gist.github.com/madwichery/53e27a4a0130fec29682487e34f97578)


## [Hasil Percobaan](https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran/)

![](/docs/3 Best Epoch v f1_score.png) 
- 3 Arsitektur sebagai skenario percobaan, mencari parameter yang bisa ditraining lebih lanjut dengan parameter yang tidak overfit dengan nilai f1 tiap arsitektur mengalami kenaikan sebesar yaitu 43,1%, 46%, dan 46,4%.

![](/docs/3 Confusion Matrix.png) 
- Hasil Klasifikasi terbaik dari ketiga parameter Arsitektur ketiga di atas.


## Diseminasi Penelitian (2022)
- Judul: **3 Tugas Content-Based Audio Retrieval Dalam Music Information Retrieval**
- Dengan tujuan untuk mendapatkan informasi dari suara yang didengar, terdapat beberapa pendekatan untuk membuat sistem mengambil informasi suara berbasis konten (content-based) dari database yang berisi cuplikan suara tersebut atau aspek yang mirip dengan kueri suara yang di dengarkan.
- Link Buku dan Presentasi:
- [[2 1157010043 - STUDI LITERATUR - MUHAMMAD AURIZ DWICHERY.pdf]]

## LKTI IPPBMM VIII (2021)
- Title:  **DETEKSI SUARA BACAAN SURAT DAN AYAT AL-QUR’AN MENGGUNAKAN LSTM DEEP LEARNING**
- Finished babak grand Finalist from 20 UIN across Java.
- Membuat sistem deteksi ayat dan surat dari suara Al-Qur'an menggunakan surat Al-Fatihah, berhasil masuk ke finalis sebagai ketua kelompok tim mewakili UIN Bandung. Menggunakan Python, Keras untuk pelatihan, Librosa untuk audio processing, dan library analitik lainnya.
- [[1 Sertifikat Peserta LKTI-Muhammad Auriz Dwichery.pdf]]
- [[1 Sertifikat Harapan II LKTI.pdf]]
- [[1 Foto LKTI 1.jpeg]]
- [Link Projek](https://github.com/madwichery/LKTI)

## Penelitian Lainnya
### KLASIFIKASI TEKS BERITA ISLAM DENGAN METODE NAIVE BAYES MULTINOMIAL, BERNOULLI DAN GAUSSIAN (2023)
- Memberikan bantuan secara keseluruhan dalam proses koding dan studi literatur. Mengklasifikasikan teks berita islam ke tiap tiap kategorinya, Hasil penelitian menunjukkan bahwa model kejadian multinomial memberikan akurasi tertinggi, sedangkan model kejadian _gaussian_ memberikan akurasi terendah untuk klasifikasi. Menggunakan python di Google Colab. 
- [[4 Perbandingan Hasil Akurasi Naive Bayes dengan k=9.png]]
Perbandingan Hasil Akurasi _Naive Bayes_ dengan k=9 - [Sumber](https://digilib.uinsgd.ac.id/8033/)
- [Source Code](https://github.com/madwichery/klasifikasi-berita-islami)

### ANALISIS METODE INFORMATION RETRIEVAL BOOLEAN MODEL DAN VECTOR SPACE MODEL MENGGUNAKAN DATA AL-QUR’AN DAN HADIS (2022)
- Membantu tahap studi literatur dan koding, membandingkan metode temu kembali informasi dengan hasil Vector Space Model pada umumnya lebih baik menggunakan data teks Al-Qur'an dan Hadis. Menggunakan Python di Google Colab. 
- [[4 Perbandingan bobot perolehan Boolean Model dan Vector Space Model untuk semua skenario.png]]
Perbandingan bobot perolehan Boolean Model dan Vector Space Model untuk semua skenario. - [Sumber](https://digilib.uinsgd.ac.id/56663/)
- [Source Code](https://github.com/madwichery/Information-retrieval)

# **Programming projects:**
## Sistem Informasi Pengelolaan Kapal dan Muatan di Pelabuhan Indonesia)
- Membuat Sistem Pengelolaan Kapal di Pelabuhan untuk mengotomatisasi sistem pembayaran pandu (pilot) menggunakan J2SE dan MySQL sesuai dengan peraturan perusahaan beberapa parameter diantaranya kapal dan waktu.
- ![[5 SIPKS.pdf]]
## Pengelolaan Inventory & Penjualan Toko.
- Membuat pengelolaan stok inventory dan penjualan toko herbal menggunakan J2SE dan MySQL.
![[5 herbalInventory.pdf]]

# Teaching projects:

## Asisten Dosen Mata Kuliah Islam dan Matematika (2022, 2023)
- Menggabungkan dan merampungkan hasil karya chapter book Islam dan Matematika.
- Menjadi tim penguji tugas akhir. 

## Asisten Dosen Mata Kuliah Dasar Pemrograman (2021, 2022)
- Menjadi tutor dalam setiap perkuliahan.
- Menjadi tim penguji tugas akhir. 
- Menggunakan Replit sebagai IDE yang diintegrasikan dengan Google Classroom. 

## Pemateri Tutorial Excel (2021 & 2022)
- Sebagai pemateri live session salah satu program pengabdian jurusan matematika UIN bandung selama 12 minggu yang dikemas dalam bentuk online course. 
- Ikut merancang dan membuat modul dalam bentuk video, dengan peserta 161 (2022) dan 143 (2021) diantara pesertanya adalah mahasiswa tahun pertama, guru SD, SMP, dan SMA sebandung, dan umum.
- [Playlist Video](https://www.youtube.com/playlist?list=PL4Lrbr1drdDxurU5EKfb7Gr2VQpsS-lTG)