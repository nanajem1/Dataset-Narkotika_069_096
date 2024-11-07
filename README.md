<p align="center">
  <img src="https://github.com/nanajem1/codelab/blob/main/logoedit2-20240819070650.png?raw=true" alt="logo" width="200">
</p>

<h2 align="center"><strong>Analisis Data Putusan Pengadilan Negeri Jakarta Timur</strong></h2>

---

## Deskripsi Dataset
Dataset ini berisi informasi mengenai putusan pengadilan di Pengadilan Negeri Jakarta Timur terkait kasus tindak pidana narkotika. Disusun dengan tujuan untuk membantu analisis teks hukum, dataset ini menyediakan data penting yang dapat mengungkap pola keputusan, pengaruh barang bukti, serta tren hukum dalam kasus narkotika.

Dataset ini memungkinkan berbagai analisis, seperti:
- **Analisis Pola Keputusan**: Mengidentifikasi tren dalam putusan hakim, seperti kecenderungan hukuman berdasarkan jenis barang bukti.
- **Penambangan Data Hukum**: Menyaring informasi penting yang dapat digunakan untuk analisis lanjutan atau sebagai data dasar untuk model prediksi.
- **Pengembangan Model NLP**: Dataset ini dapat digunakan untuk melatih model pemrosesan bahasa alami (NLP) dalam konteks hukum, termasuk klasifikasi teks atau ekstraksi entitas khusus hukum.

## Sumber Data
Dataset ini dikumpulkan dari sumber-sumber publik, termasuk situs resmi Pengadilan Negeri Jakarta Timur dan dokumen-dokumen terkait yang tersedia untuk umum. Setiap catatan dalam dataset ini mewakili putusan resmi yang diambil dari dokumentasi pengadilan yang sah. 

[Dataset Narkotika PN Jakarta Timur](https://github.com/nanajem1/Dataset-Narkotika_069_096/blob/main/Overview/Overview.xlsx)


## Isi Dataset
Dataset ini terdiri dari kolom-kolom berikut, yang masing-masing menyajikan elemen penting dari putusan pengadilan:

- **NO**: Nomor urut yang unik untuk setiap entri dalam dataset.
- **No Putusan**: Kode unik yang mewakili nomor putusan, seperti "13/Pid.Sus/2023/PN Jkt.Tim", yang menunjukkan identifikasi kasus di pengadilan.
- **Lembaga Peradilan**: Nama lembaga pengadilan yang memutuskan kasus, dalam hal ini "PN Jakarta Timur", yang dapat digunakan untuk mengidentifikasi yurisdiksi.
- **Barang Bukti**: Informasi rinci tentang barang bukti yang ditemukan, seperti jumlah dan jenis narkotika atau benda terkait. Kolom ini mencakup deskripsi yang dapat digunakan untuk mengidentifikasi pola dalam bukti yang diajukan.
- **Amar Putusan**: Ringkasan keputusan hakim terhadap terdakwa, mencakup keterangan bersalah/tidak bersalah, jenis hukuman, dan rincian lain terkait putusan.

## Contoh Data
Berikut adalah contoh beberapa entri dalam dataset:

| NO | No Putusan           | Lembaga Peradilan | Barang Bukti                                | Amar Putusan                                  |
|----|-----------------------|-------------------|---------------------------------------------|-----------------------------------------------|
| 1  | 13/Pid.Sus/2023/PN Jkt.Tim | PN Jakarta Timur  | 1 kantong plastik berisi sabu              | Menyatakan terdakwa bersalah, hukuman penjara |
| 2  | 40/Pid.Sus/2023/PN Jkt.Tim | PN Jakarta Timur  | 2 kotak stainless berisi ganja             | Menyatakan terdakwa bersalah, hukuman penjara |
| 3  | 41/Pid.Sus/2023/PN Jkt.Tim | PN Jakarta Timur  | 1 dompet berisi pil ekstasi                | Menyatakan terdakwa bersalah, hukuman penjara |

## Potensi Penggunaan Dataset
Dataset ini memiliki banyak potensi penggunaan dalam berbagai bidang:

- **Penelitian Hukum**: Peneliti dapat menggunakan dataset ini untuk mengidentifikasi tren hukuman atau pola putusan dalam kasus narkotika. Analisis ini berguna untuk mengevaluasi konsistensi putusan dalam kasus-kasus serupa.
- **Pengembangan Algoritma NLP untuk Dokumen Hukum**: Dataset ini bisa digunakan untuk melatih model Natural Language Processing yang berfokus pada teks hukum. Contohnya, model untuk klasifikasi kasus, identifikasi entitas hukum, atau analisis sentimen putusan.
- **Pembelajaran Mesin untuk Prediksi Putusan**: Dengan data yang cukup, algoritma pembelajaran mesin bisa dilatih untuk memprediksi jenis hukuman atau hasil putusan berdasarkan pola tertentu pada barang bukti dan faktor lainnya.
- **Analisis Kebijakan Publik**: Dataset ini dapat menjadi dasar bagi pembuat kebijakan untuk memahami pola dalam penanganan kasus narkotika dan efek kebijakan terhadap keputusan pengadilan.

## Analisis Note
- **Kepentingan Analisis**: Dataset ini disusun untuk kepentingan analisis tekstual, akademik, dan penelitian hukum. Pengguna diharapkan untuk menggunakan dataset ini dengan bijak dan hanya untuk tujuan non-komersial. Penggunaan komersial memerlukan izin tertulis.
- **Privasi**: Dataset ini tidak mengandung data pribadi terdakwa yang sensitif atau data identitas lainnya yang dapat mengarah pada individu tertentu. Hanya informasi umum dan publik terkait kasus yang dimasukkan.
- **Keterbatasan Data**: Dataset ini mungkin tidak mencakup semua putusan atau informasi terbaru, mengingat data diambil dari sumber sekunder yang terbatas dan disusun secara manual. Pengguna perlu mempertimbangkan bahwa dataset ini mungkin memiliki beberapa keterbatasan dalam hal kelengkapan dan akurasi.

