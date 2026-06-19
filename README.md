# Spotify Music Analytics — SQL & Data Visualization

Analisis data 953 lagu populer Spotify menggunakan SQL (MySQL) dan 
visualisasi interaktif di Looker Studio. Project ini dibuat sebagai 
latihan end-to-end data analyst workflow: dari data cleaning sampai 
dashboard siap presentasi.

## Business Context

Berperan sebagai Data Analyst di sebuah label musik yang ingin memahami 
tren musik populer untuk mendukung keputusan A&R (Artist & Repertoire) 
— termasuk strategi rilis lagu dan evaluasi performa artis.

## Tools

- **MySQL Workbench** — data cleaning, EDA, dan analisis
- **Looker Studio** — dashboard visualisasi interaktif

## Pertanyaan Bisnis yang Dijawab

1. Siapa artis paling dominan berdasarkan total streams?
2. Kapan waktu terbaik merilis lagu (bulan/tahun)?
3. Apakah jumlah playlist berkorelasi dengan jumlah streams?
4. Bagaimana tren musik dari tahun ke tahun (YoY growth)?
5. Lagu solo vs kolaborasi — mana yang lebih sukses?
6. Karakteristik audio apa yang dimiliki lagu hits?
7. Siapa artis paling konsisten (bukan cuma populer sesaat)?
8. Lagu mana yang overperform dibanding rata-rata tahunnya?

## Teknik SQL yang Digunakan
- Data cleaning (deteksi NULL, duplikat, validasi tipe data)
- Aggregation (`GROUP BY`, `HAVING`)
- `CASE WHEN` untuk segmentasi data
- Common Table Expression (CTE) — termasuk CTE berantai
- Window Functions: `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`, 
  `LAG()`, `PARTITION BY`, running total
