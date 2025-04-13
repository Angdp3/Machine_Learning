<!--- Agglomerative Clustering & GeoPandas Map Visualization
📌 Deskripsi Proyek

Proyek ini menggunakan Agglomerative Clustering untuk melakukan segmentasi data demam berdarah di Kota Semarang, kemudian hasil clustering divisualisasikan dalam bentuk peta menggunakan GeoPandas.

📊 Teknologi yang Digunakan

Python (NumPy, Pandas, Matplotlib, Seaborn)

Scikit-learn (Agglomerative Clustering)

GeoPandas (Visualisasi peta berbasis geospasial)
--->

# 🦟 DBD Clustering Analysis - Hierarchical Clustering

📌 Deskripsi Proyek
Proyek ini bertujuan untuk mengelompokkan wilayah berdasarkan tingkat kasus Demam Berdarah Dengue (DBD) menggunakan teknik Hierarchical Clustering. Dengan pendekatan ini, diharapkan dapat ditemukan pola geografis yang signifikan sebagai dasar pengambilan keputusan pencegahan dan penanganan DBD secara lebih tepat sasaran.

Data bersumber dari jumlah kasus DBD per kecamatan dalam beberapa tahun terakhir (misalnya 2021–2023).
---
## Tujuan Analisis
- Mengelompokkan kelurahan berdasarkan kemiripan jumlah kasus DBD.
- Mengidentifikasi wilayah dengan risiko tinggi, sedang, dan rendah.
- Menyediakan dasar analitik untuk kebijakan kesehatan masyarakat.
---
## Langkah-Langkah Proyek
- Data Cleaning & Preprocessing
  - Cek data duplikat dan missing values
  - Normalisasi data jumlah kasus DBD agar sebanding antar Kelurahan
- Exploratory Data Analysis (EDA)
  - Meninjau tren tahunan dan distribusi kasus
  - Mencari outlier  
- Hierarchical Clustering
  - Menggunakan metode agglomerative clustering
  - Visualisasi menggunakan dendrogram untuk melihat hubungan antar wilayah
- Interpretasi Cluster
  - Setiap cluster dianalisis untuk memahami karakteristiknya
  - Visualisasi dengan Geopandas
---
Gambar dibawah adalah preview project
![download (4)](https://github.com/user-attachments/assets/54ae1005-4e05-43c1-a84c-5df23b2acf80)
![download](https://github.com/user-attachments/assets/b9232d19-a8dc-41a3-a7a1-10fb70e3f3d5)
