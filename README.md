PROJECT PLAN
Validasi Limit yang Gagal? — Analisis Risiko Kredit GoPayLater
Nazma Aulia • Thomas Dani Haryanto • M. Aldi Riansyah | JCDSBSD-34 | 17 September 2026

Konteks & Problem
GoPayLater — fitur kredit berbasis limit dalam ekosistem GoPay — menunjukkan tren NPL yang meningkat. Temuan kritis: >50% transaksi GoPayLater melebihi paylater_limit user, termasuk dari tier Basic yang seharusnya tidak punya akses PayLater — mengindikasikan bug sistemik pada validasi limit kredit.

Tujuan Proyek

Membersihkan data users, services, dan transactions GoPay.
Membangun fitur analisis risiko kredit & perilaku pengguna.
Mengidentifikasi pola gagal bayar dan anomali sistem PayLater.
Menyusun rekomendasi perbaikan credit scoring berbasis data.

Ruang Lingkup

Termasuk: cleaning 3 dataset, feature engineering, EDA berbasis pandas (tanpa visualisasi), investigasi bug limit, export dataset final.
Tidak termasuk: pembangunan model ML, visualisasi grafis, implementasi perbaikan sistem.

Jadwal & Pembagian Tugas

Fase 1 — Data & Business Understanding 
Fase 2 — Data Cleaning (missing value, payment_method, late_fee, anomali tanggal, business logic error)
Fase 3 — Feature Engineering (fitur wajib + pilihan)
Fase 4 — Exploratory Data Analysis & Insight
Fase 5 — Export Dataset Final & Presentasi— Seluruh Tim

Kriteria Keberhasilan

gopay_clean.csv tergabung tanpa error, terdokumentasi tiap tahap cleaning.
7 fitur wajib + minimal 2 fitur pilihan selesai dengan justifikasi business value.
Investigasi bug limit PayLater tersampaikan dengan reasoning yang jelas.
Rekomendasi credit scoring: minimal 3 variabel prediktor + 1 kebijakan konkret.
