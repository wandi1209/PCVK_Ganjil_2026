# PCVK_Ganjil_2026

Praktikum Pengolahan Citra dan Visi Komputer.

- `Modul 1/` - Modul_1_D1, D2, D3, dan tugas kelompok
- `Modul 2/` - Modul_2.ipynb
- `Modul 3/` - Modul_3.ipynb
- `Modul 5/` - Week5_26.ipynb (histogram, histogram equalization, dithering)
- `Modul 6/` - Modul_6_D, Modul_6_E, dan Tugas_Praktikum_PCVK (filter spasial dan filter modern)
- `Modul 7/` - Week7.ipynb (segmentasi: global/adaptive/Otsu threshold manual, region growing, flood, K-Means) dan Tugas_Kelompok_Week7.ipynb (OCR KTP)

Notebook dijalankan di Google Colab.

Modul 3 membaca citra dari `/content/drive/MyDrive/PCVK/Images/` (houses.jpg, peppers.jpg,
galaxy.jpg, noises/, couple.tiff, crayfish.jpg, malam.jpg).

Modul 5 memakai dua folder: `Images/` untuk citra contoh (lena.jpg, lena_lc.jpg) dan
`Images/<NIM>/` untuk citra KTM hasil akuisisi Pertemuan 2 (KTM1a.jpg sampai KTM1d.jpg).
Parameter percobaan Modul 5 (bins, clipLimit, tileGridSize, jumlah level dithering) dihitung
dari tiga digit terakhir NIM pada sel identitas.

Modul 7 memakai citra contoh dari `Images/` (gradient.jpg, sudoku-original.jpg,
lena_gs_lc2.jpg, ktp_fulan.jpg), citra `coins` dari skimage, dan citra KTP sendiri di
`Images/<NIM>/`. Bagian global threshold, adaptive threshold, dan Otsu dibuat manual dengan
NumPy; pemanggilan OpenCV hanya dipakai di sel verifikasi untuk membandingkan hasil.
