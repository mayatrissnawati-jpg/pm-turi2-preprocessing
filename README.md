Preprocessing & Feature Engineering

Mata Kuliah: Pembelajaran Mesin (INF62325)
Nama: Maya Trisnawati
NIM: (isi NIM Anda)

Ringkasan
Praktikum ini membahas preprocessing dan feature engineering pada data, meliputi penanganan nilai hilang, encoding data kategorikal, pembagian data training dan testing, serta scaling menggunakan StandardScaler dan MinMaxScaler.

Isi Repositori
`PM_P4_Maya-Trisnawati_2488010050.ipynb` : notebook praktikum
Temuan Utama
- Nilai hilang pada data ditangani menggunakan imputasi median dan pada latihan dibandingkan dengan mean.
- Data kategorikal `pendidikan` diubah menjadi nilai numerik, sedangkan `kota` dan `jenis_kelamin` diubah menggunakan one-hot encoding.
- Data dibagi menjadi data training dan testing sebelum dilakukan scaling untuk mencegah terjadinya data leakage.
- StandardScaler dan MinMaxScaler digunakan untuk menyamakan skala fitur numerik.
