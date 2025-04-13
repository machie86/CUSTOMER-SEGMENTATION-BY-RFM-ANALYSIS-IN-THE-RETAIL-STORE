# Optimizing Retail Business Strategy through RFM-Based Customer Segmentation and Demographic Profiling

## Overview
Proyek ini bertujuan untuk mengoptimalkan strategi bisnis ritel dengan melakukan segmentasi pelanggan menggunakan analisis RFM (Recency, Frequency, Monetary) dan profil demografis. Analisis ini dilakukan pada dataset "Supermarket Customers" yang berisi data 2.240 pelanggan, mencakup riwayat pembelian, demografi, dan pola pengeluaran. Proyek ini memberikan wawasan tentang perilaku pelanggan, segmentasi, serta rekomendasi strategi pemasaran untuk meningkatkan pendapatan dan loyalitas pelanggan.

## Dataset
Dataset `Supermarket_Customer_Cleaned.csv` berisi informasi tentang 2.240 pelanggan dengan 29 kolom yang dikelompokkan ke dalam kategori berikut:
- **People**: Demografi pelanggan (usia, pendidikan, status pernikahan, pendapatan, komposisi keluarga, dll.)
- **Products**: Pengeluaran untuk produk (anggur, buah, daging, ikan, permen, emas)
- **Promotion**: Respons pelanggan terhadap kampanye pemasaran
- **Place**: Saluran pembelian (web, katalog, toko) dan aktivitas online

Setelah pembersihan data, dataset memiliki 2.202 pelanggan yang digunakan untuk analisis.

## Objectives
- Mensegmentasi pelanggan ke dalam kategori High-Value, Medium-Value, dan Low-Value berdasarkan skor RFM.
- Mengidentifikasi strategi retensi untuk pelanggan berisiko churn (segmen "At Risk").
- Menganalisis pengaruh demografis (usia, pendidikan, komposisi keluarga) terhadap pola pengeluaran.
- Memberikan rekomendasi untuk meningkatkan pendapatan melalui upselling, cross-selling, dan strategi pemasaran berbasis demografis.
- Mengoptimalkan strategi produk dan pemasaran berdasarkan preferensi pelanggan.

## Key Findings
- **Segmentasi RFM**:
  - High-Value: 43% (942 pelanggan), rata-rata pengeluaran $1,153.46.
  - Medium-Value: 36% (801 pelanggan), rata-rata pengeluaran $278.52.
  - Low-Value: 21% (459 pelanggan), dengan segmen "At Risk" (22%) berisiko churn.
- **Pengaruh Demografis**:
  - Pelanggan dengan pendidikan tinggi (PhD, Master) menghabiskan lebih banyak ($610–$678).
  - Pelanggan tanpa anak/remaja menghabiskan lebih banyak ($1,419).
  - Kelompok usia 36–45 tahun adalah target pasar utama.
- **Distribusi Segmen**:
  - High-Value dan Medium-Value mencakup 79% pelanggan.
  - Segmen "At Risk" (22%) perlu perhatian untuk mencegah churn.

## Recommendations
- **Retensi "At Risk"**: Luncurkan kampanye re-engagement (diskon, email personalisasi).
- **High-Value**: Tawarkan produk premium (Wine, Meat) dan program loyalitas.
- **Medium-Value**: Dorong pembelian dengan bundling produk (Fruits-Sweet, Meat-Fish).
- **Strategi Demografis**:
  - Targetkan pelanggan dengan pendidikan tinggi untuk produk premium.
  - Promosikan produk mewah (Gold) untuk pelanggan tanpa anak/remaja.
  - Fokuskan kampanye pada usia 36–45 tahun.
- **Optimalisasi Produk**: Prioritaskan Wine (50.3%) dan Meat (27.5%), dorong penjualan Gold dan Fish melalui bundling.

## Project Structure
```
├── Supermarket_Customers.ipynb  # Notebook utama berisi analisis dan visualisasi
├── Supermarket_Customer_Cleaned.csv  # Dataset yang digunakan
└── README.md  # Dokumentasi proyek
```

## Dependencies
Proyek ini menggunakan Python 3.11 dan library berikut:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

Untuk menginstal dependensi, jalankan:
```bash
pip install -r requirements.txt
```

Atau instal secara manual:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

## How to Run
1. Clone repository ini:
   ```bash
](https://github.com/machie86/CUSTOMER-SEGMENTATION-BY-RFM-ANALYSIS-IN-THE-RETAIL-STORE/edit/main/README.md)   ```

2. Masuk ke direktori proyek:
   ```bash
   cd <CUSTOMER-SEGMENTATION-BY-RFM-ANALYSIS-IN-THE-RETAIL-STORE>
   ```
3. Pastikan dependensi terinstal (lihat bagian Dependencies).
4. Buka Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Jalankan `Supermarket_Customers.ipynb` untuk melihat analisis dan hasilnya.

## Next Steps
- Implementasikan kampanye re-engagement untuk segmen "At Risk" dalam 1–2 bulan.
- Uji strategi bundling pada segmen Medium-Value.
- Analisis lebih lanjut pengaruh pendapatan terhadap preferensi produk untuk segmentasi yang lebih mendalam.

## Acknowledgments
- Dataset diadaptasi dari sumber data ritel untuk keperluan analisis.
- Terima kasih kepada komunitas open-source atas library yang digunakan.
