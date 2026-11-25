
# DJPK APBD dan Pajak Daerah Jawa Timur 2011–2026

Repository dataset Anggaran Pendapatan dan Belanja Daerah (APBD) serta Pajak Daerah untuk kabupaten/kota di Provinsi Jawa Timur.

Data dikumpulkan dari portal resmi **Direktorat Jenderal Perimbangan Keuangan (DJPK), Kementerian Keuangan Republik Indonesia** dan disusun dalam format CSV agar lebih mudah digunakan untuk analisis data, penelitian, visualisasi, maupun pemodelan machine learning.

## 📊 Dataset

### 1. Dataset APBD Jawa Timur 2020–2026

File:

`DJPK_Jawa_Timur_APBD_2020_2026.csv`

Dataset mencakup data Anggaran Pendapatan dan Belanja Daerah (APBD) kabupaten/kota di Provinsi Jawa Timur selama periode 2020–2026.

Cakupan wilayah meliputi pemerintah daerah kabupaten/kota di Provinsi Jawa Timur yang tersedia pada portal DJPK.

### 2. Dataset Pajak Daerah Jawa Timur 2011–2026

File:

`pajak_daerah_jatim_2011_2026.csv`

Dataset ini berisi data anggaran dan realisasi penerimaan pajak daerah pada seluruh kabupaten/kota di Provinsi Jawa Timur selama periode 2011–2026.

Dataset disusun dalam bentuk data panel (panel data), yaitu kombinasi data antarwilayah (cross-sectional) dan antarwaktu (time series).

#### Dataset Overview

| Attribute | Description |
|---|---|
| Province | Jawa Timur |
| Period | 2011–2026 |
| Total Years | 16 tahun |
| Total Regions | 38 kabupaten/kota |
| Total Records | 608 baris |
| Total Columns | 16 kolom |
| Available Records | 595 baris |
| Missing Records | 13 baris |
| Data Format | CSV |
| Currency | Indonesian Rupiah (IDR) |
| Collection Date | 4 November 2026 |
| Data Source | DJPK Kementerian Keuangan RI |

#### Data Dictionary

| Column | Description |
|---|---|
| `tahun` | Tahun anggaran |
| `provinsi` | Nama provinsi |
| `kode_provinsi_djpk` | Kode provinsi berdasarkan DJPK |
| `kabupaten_kota` | Nama kabupaten/kota |
| `kode_pemda_djpk` | Kode pemerintah daerah berdasarkan DJPK |
| `akun` | Jenis akun pendapatan, yaitu Pajak Daerah |
| `anggaran_pajak_rp` | Target anggaran pajak daerah dalam rupiah |
| `realisasi_pajak_rp` | Realisasi penerimaan pajak daerah dalam rupiah |
| `persen_realisasi` | Persentase realisasi terhadap anggaran pajak daerah |
| `periode_diminta` | Periode pelaporan yang diminta pada portal DJPK |
| `judul_sumber` | Judul halaman sumber data |
| `keterangan_djpk` | Keterangan pelaporan dari portal DJPK |
| `status` | Status keberhasilan pengambilan data |
| `catatan` | Catatan tambahan mengenai kondisi data |
| `url_sumber` | URL sumber data resmi DJPK |
| `diambil_pada_wib` | Waktu pengambilan data dalam WIB |

## 🏛️ Data Source

Data bersumber dari:

**Direktorat Jenderal Perimbangan Keuangan (DJPK)**  
**Kementerian Keuangan Republik Indonesia**

Portal Data APBD:  
https://djpk.kemenkeu.go.id/portal/data/apbd

Data pada repository ini merupakan hasil pengumpulan dan penyusunan kembali data publik dari portal DJPK untuk kepentingan penelitian dan analisis.

## 🎯 Purpose

Dataset ini dapat digunakan untuk berbagai kebutuhan penelitian, antara lain:

- Analisis perkembangan APBD kabupaten/kota di Jawa Timur
- Analisis pendapatan dan belanja pemerintah daerah
- Analisis perkembangan penerimaan pajak daerah
- Analisis efektivitas realisasi pajak daerah
- Analisis pertumbuhan pajak daerah antartahun
- Analisis fiskal dan keuangan daerah
- Perbandingan kinerja keuangan antarwilayah
- Analisis potensi Pendapatan Asli Daerah (PAD)
- Analisis tren jangka panjang periode 2011–2026
- Analisis data panel (panel data analysis)
- Pemodelan ekonometrika dan statistik
- Peramalan penerimaan pajak daerah (forecasting)
- Pemodelan machine learning
- Pengembangan dashboard dan visualisasi data
- Penelitian ekonomi, kebijakan publik, dan keuangan daerah

## 📁 Repository Structure

```text
DJPK-APBD-Jawa-Timur-2020-2026/
│
├── DJPK_Jawa_Timur_APBD_2020_2026.csv
├── pajak_daerah_jatim_2011_2026.csv
└── README.md
```

## 📚 Citation
Direktorat Jenderal Perimbangan Keuangan (DJPK).
Kementerian Keuangan Republik Indonesia.
Portal Data Anggaran Pendapatan dan Belanja Daerah (APBD).
https://djpk.kemenkeu.go.id/portal/data/apbd
Repository ini bukan merupakan publikasi resmi Kementerian Keuangan Republik Indonesia. Untuk memperoleh data resmi dan pembaruan terkini, silakan mengakses portal DJPK secara langsung.
