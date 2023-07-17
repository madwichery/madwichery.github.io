---
title: "Klasifikasi Ayat Al-Qur'an dengan Mel Frequency Cepstral Coefficient (MFCC) dan Artificial Neural Network (ANN)"
date: 2022-11-23T22:00:00Z
slug: "klasifikasi-surat-ayat-al-quran"
description: "Skripsi Saya yaitu: Membuat Model untuk Mengetahui Surat dan Ayat dari Suara Al-Qur'an."
categories: ["Riset"]
tags: ["2022", "Riset"]
tools: ["Python"]
featured: true
toc: true
---

## Abstrak
Penelitian ini bertujuan untuk mengembangkan sebuah model Artificial Neural Network (ANN) yang dapat mengenali ayat-ayat dan surah dalam Al- Qur'an melalui penggunaan suara. Para penuntut ilmu agama yang ingin memperdalam pemahaman tentang ayat-ayat Al-Qur'an dapat memanfaatkan teknologi ini untuk mengidentifikasi ayat-ayat tertentu dengan menunjukkan nomor surah dan ayat yang dimaksud. Penelitian ini menggunakan data Al-Qur'an terbatas pada 7 surah dan 32 ayat, serta 31 dataset qari dengan kualitas audio bitrate lebih besar dari 128 kbps dan sampling rate 22050. Metode yang digunakan meliputi tahap-tahap preprocessing data dengan menggunakan MFCC, training dan testing model ANN dilakukan melalui pembagian dataset menjadi data train, validation, dan test. Evaluasi dilakukan dengan menggunakan seluruh data test pada model, dan model terbaik serta optimal dipilih untuk dianalisis hasilnya berdasarkan metrik-metrik yang telah ditentukan sebelumnya, yaitu f- measure, precision, recall, ROC-AUC, dan akurasi. Meskipun hasil penelitian menunjukkan bahwa model terbaik untuk setiap arsitektur masih memerlukan peningkatan dalam kemampuan prediksi, namun beberapa hasil menunjukkan bahwa arsitektur 1, 2, dan 3 memiliki akurasi berturut-turut sebesar 43,1%, 46%, dan 46,4%

| Platform                        | URL                                                                                                                                                                                                                         |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Github                          | [Github Link Repository](https://github.com/madwichery/klasifikasi-suara-quran-dengan-ann-dan-mfcc)                                                                                                                         |
| Weight And Biases (*Grafik* dan *Tabel* seluruh penelitian)               | [WANDB Link Repository](https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran?workspace=user-)                                                                                                           |
| Exploratory Data Analysis (EDA) | [WANDB EDA Report]((https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran-EDA/reports/Exploratory-Data-Analysis-Skripsi-Menghadapi-Variabilitas-Durasi-Audio-dalam-Tugas-Klasifikasi--VmlldzozODI2NzUx)) |
| Data suara yang digunakan                 | [WANDB Artifact]((https://wandb.ai/madwichery/skripsi-madwichery-klasifikasi-32-ayat-quran-EDA/artifacts/dataset/raw-dataset/v0/files))                                                                                     |
|                                 |                                                                                                                                                                                                                             |

---

- Mengidentifikasi suara Al-Qur'an yang dibacakan sesuai dengan surat dan ayatnya. Menggunakan skema MLOps (Machine Learning Operations) dengan library **Weight and Biases** (WANDB).