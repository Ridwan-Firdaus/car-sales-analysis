# Analisis Penjualan Mobil

## Latar Belakang
Proyek ini bertujuan untuk menganalisis data penjualan mobil di Amerika Serikat selama tahun 2022 dan 2023. Fokus utama meliputi identifikasi tren penjualan bulanan, karakteristik demografi konsumen, serta evaluasi performa dealer berdasarkan wilayah. Analisis juga mencakup distribusi harga dan penanganan outlier.

## Pernyataan Masalah
- Analisis demografi pembeli mobil.
- Analisis trend penjualan mobil dari tahun 2022–2023.
- Analisis dealer dengan potensi penjualan tinggi.

## Analisis
1. **Data Cleaning**
   - Menghapus data duplikat
   - Handling missing value
   - Deteksi dan perlakuan terhadap outlier menggunakan metode IQR

2. **Analisis Eksploratif**
   - Demografi: gender, pendapatan
   - Tren penjualan per bulan
   - Performa dealer dan wilayah
   - Distribusi harga dan korelasi

3. **Visualisasi**
   - Histogram, boxplot, bar chart, line plot, regresi (regplot)

## Insight Utama
- Penjualan mobil memuncak pada bulan Desember 2023, dengan peningkatan signifikan di bulan September dan November.
- Terjadi tren peningkatan penjualan dari tahun 2022 ke 2023, kemungkinan besar karena pemulihan pasca pandemi COVID-19.
- Mayoritas pembeli mobil adalah pria dengan pendapatan tahunan tinggi.
- Wilayah dealer seperti Austin, Janesville, dan Scottsdale mencatatkan total penjualan tertinggi.
- Tidak ditemukan hubungan yang signifikan antara harga rata-rata mobil dengan jumlah penjualan bulanan.

## Rekomendasi Bisnis
- Fokus promosi penjualan di akhir tahun (September–Desember), khususnya saat momen Thanksgiving dan Natal.
- Tingkatkan strategi pemasaran untuk menjangkau pembeli perempuan yang masih rendah jumlahnya.
- Tawarkan produk premium dan layanan eksklusif untuk segmen konsumen berpendapatan tinggi.
- Pertimbangkan ekspansi jaringan dealer di wilayah dengan performa penjualan tinggi seperti Austin Janesville, dan Scotsdale.

## Tools yang digunakan
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Dataset digunakan dalam file: `car_sales_analysis.ipynb`