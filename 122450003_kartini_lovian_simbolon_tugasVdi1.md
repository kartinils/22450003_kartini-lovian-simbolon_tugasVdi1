---
jupyter:
  colab:
  kernelspec:
    display_name: Python 3
    name: python3
  language_info:
    name: python
  nbformat: 4
  nbformat_minor: 0
---

::: {.cell .markdown id="GG0A4ip8GFy_"}
Nama : kartini lovian simbolon

Nim : 1233450003

Kelas :Rc
:::

::: {.cell .markdown id="TM-989u7GpWi"}
**pendahuluan**

visualisasi data merupakan perubahan dari data abstrak diubah menjadi
data yang berbentuk gambar,sehingga dengan adanya visualisasi lebih
membuat orang mudah memahami data tersebut dan banyak oraganisasi
menggunakan visualisasi ini sehingga mudah untuk ditafsirkan.

terdapat komunitas yang memberikan rekomendasi untuk memudahkan pengguna
melakukan visualisasi contohnya dengan D3,VegaLite,Tableu,dan microsoft
power BI
:::

::: {.cell .markdown id="PTHcNGu7svjo"}
**Tujuan penelitian**

untuk menangggapi permintaan membantu visualisasi data yang lebih
efisien dan lebih efektif karena tingginya permintaan pemrosesan data
:::

::: {.cell .markdown id="x8GRDpyhta9P"}
**Metode yang dipakai**

pada jurnal ini metode yang dipakai menggunakan studi literatur dan
memakai kualitatif
:::

::: {.cell .markdown id="aiNc71K0Mksx"}
**alur dari visualisasi data**

-   data import

-   data preparation

-   mapping

-   rendering

dari alur diatas dapat diidentikasikan menjadi 3 yaitu

-   **Visualization Specifications**

bahasa dari visualisasi data dibagi menjadi 3 yaitu data,marks,dan
mapping

dalam visualisasi terdadapat kategori terdapat underspecified lalu
diatasnya ada gui-bassed tools,high-level,dan low-level semakin tinggi
level nya semakin mudah digunakan

-   **Efficient Approaches for Data Visualization**

efisiensi dibutuhkan dalam pemilihan visualisasi data yang tepat seperti
cara membaca data dari data base atau ketika memilih query yang tepat
untuk digunakan

terdapat juga visualisasi dengan data perkiraan dimana ada 3 perkiraan
yaituAQP-based approaches that leverage techniques from AQP; incremental
sampling-based approaches that link incremental query processing to
visualization; and human perception-based approaches that capture the
cognitive limitations of human perception

-   **visualisasi data progresif**

visualisasi progresif melalui agregasi hierarkis.visualisasi progresif
melalui agregasi hierarkis. Secara umum, membangun struktur hierarkis
dengan menggabungkan data dalam berbagai tingkatan, misalnya, berbagai
ukuran wadah, berbagai rentang nilai temporal, berbagai zona nilai
spasial. Kemudian, struktur hierarkis ini digunakan untuk mendukung
eksplorasi visualisasi progresif pengguna. Range-Based Binning
menyediakan visualisasi resolusi yang berbeda dengan mengubah ukuran bin
Bin dengan resolusi yang sama memiliki rentang yang sama. Data
multidimensi di imMens dipartisi ke dalam kubus data, dan kubus
dipartisi ke dalam petak dengan level yang berbeda. Pengguna dapat
menjelajahi data dalam level yang berbeda dan mengubah resolusi
visualisasi.Range and Content-Based Binning HETree-C dapat digunakan
dalam skenario transkrip pemeriksaan di atas. Pengguna dapat menjelajahi
abstraksi data atau detail data dengan operasi roll-up atau drill-down
untuk mencapai level atas atau berikutnya
:::

::: {.cell .markdown id="hTd8kPHYGtco"}
-   **Rekomendasi visualisasi**

Rekomendasi berbasis spesifikasi

Sistem rekomendasi visualisasi dengan spesifikasi kosong tidak
memerlukan masukan pengguna, sementara sistem rekomendasi dengan
spesifikasi parsial menerima masukan, Sistem rekomendasi berbasis aturan
memberi peringkat kandidat visualisasi berdasarkan aturan yang telah
ditentukan sebelumnya, yang biasanya berupa metrik efektivitas persepsi
manusia

Rekomendasi berbasis perilaku

adalah sistem rekomendasi visualisasi yang digerakkan oleh perilaku.
Sistem ini merekomendasikan visualisasi berdasarkan tugas pengguna yang
disimpulkan oleh perilaku mereka

Rekomendasi yang dipersonalisasi

memberikan hasil rekomendasi visualisasi yang dipersonalisasi dengan
melatih model linier untuk setiap pengguna menggunakan perilaku historis
mereka, Selain Penyaringan Kolaboratif untuk melatih model setiap
pengguna ada banyak teknik lain yaitu penyaringan Berbasis Konten.Bagi
pengguna yang baru menggunakan sistem ini, rekomendasi berbasis CF tidak
berlaku. Dengan demikian, VizRec juga mengembangkan rekomendasi berbasis
konten.
:::

::: {.cell .markdown id="AMXoCA1qWudw"}
**Arah penelitian**

-- What-if Analysis for Outliers

memungkinkan pengguna untuk menentukan secara manual outlier dari hasil
query agregasi. Kemudian mencoba untuk menemukan dan menghapus predikat
yang menyebabkan outlier tersebut

-- Evaluating Visualizations with Missing Data

untuk mengukur faktor-faktor yang memengaruhi akurasi respons, kualitas
data, dan keyakinan dalam interpretasi untuk data deret waktu dengan
nilai yang hilang

**Tolak ukur visualisasi data**

Seperti ImageNet atau benchmark TPC klasik, penting untuk mengembangkan
tolok ukur untuk kinerja dan rekomendasi. Tolok ukur harus sesuai dengan
tugas analisis visual, menyediakan jejak dan data yang dapat digunakan
kembali
:::

::: {.cell .markdown id="vRkMXiMVZDlL"}
**kesimpulan**

dari jurnal ini dapat disimpulkan bahwa visualisasi data sudah banyak
sekali dipakai dengan berbagai teknik dan didalam jurnal ini menjelaskan
bagaimana visualisasi yang digunakan menjadi lebih efisien dan efektif
dengan membandingkan satu studi kasus dengan studi kasus lainya dan
memberikan pemahaman visualisasi ,dengan visualisasi ini juga banyak
peneliti atau pun perusahaan industri terbantu dalam mengambil keputusan
yang dapat mencapai keberhasilan,namun masih ada hal mengenai
rekomendasi dari sistem yang diperlukan diskusi lanjutan ataupun diskusi
terbuka dengan peneliti untuk membahas masalah tersebut
:::
