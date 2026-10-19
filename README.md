# UTS Graf Sains Data

## Deskripsi
Repository ini berisi dokumentasi pengerjaan Ujian Tengah Semester mata kuliah Graf Sains Data. Pengerjaan meliputi pengolahan data interaksi, eksplorasi graf, Vector Space Modeling (VSM), perhitungan similarity, serta sistem rekomendasi menggunakan metode K-Nearest Neighbors (KNN).

## Dataset
Dataset yang digunakan adalah RetailRocket e-commerce dataset.

Data dibagi menjadi dua periode:
- P1 (training): 1–15 Juli 2015.
- P2 (testing): 1–18 September 2015.

Dataset hasil pengolahan disimpan pada folder `data/processed/`.

## Struktur Repository
- `nama_file.ipynb`: notebook yang digunakan dalam pengerjaan UTS.
- `data/processed/`: dataset hasil pengolahan untuk P1 dan P2.
- `requirements.txt`: daftar pustaka Python yang diperlukan.
- `bukti/`: visualisasi pendukung hasil percobaan kode bagian 1.

## Metode
1. Filter data berdasarkan periode waktu P1 dan P2.
2. Impor data interaksi ke Neo4j dan eksplorasi komposisi graf.
3. Membentuk Vector Space Model (VSM) untuk User dan Item.
4. Menghitung similarity dan menampilkan hasilnya pada graf.
5. Membuat rekomendasi menggunakan user-based KNN dengan k = 5.
6. Mengevaluasi rekomendasi menggunakan Hit@5 dan NDCG@5.

## Cara Menjalankan
1. Unduh atau clone repository ini.
2. Instal pustaka yang tercantum dalam `requirements.txt`.
3. Siapkan database Neo4j dan konfigurasi koneksi secara lokal melalui environment variable.
4. Jalankan notebook `nama_file.ipynb` dari awal hingga akhir.
