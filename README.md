
# Proyek Analisis Sentimen dan Named Entity Recognition (NER) BPJS Kesehatan

## Deskripsi
Proyek ini bertujuan untuk menganalisis persepsi publik terhadap layanan BPJS Kesehatan melalui analisis sentimen dan pengenalan entitas bernama (NER) menggunakan teknik pemrosesan bahasa alami (NLP). Data berita dikumpulkan dari berbagai portal berita terpercaya total seperti CNN, Kompas, AntaraNews, Indozone, Detikhealth, dan CNBC, menggunakan metode web scraping, yang menghasilkan lebih dari 5.036 artikel yang telah diproses.

## Fitur Utama
- **Analisis Sentimen**: Mengidentifikasi sentimen positif, negatif, dan netral dalam berita terkait BPJS Kesehatan.
- **Clustering**: Mengelompokkan berita menggunakan metode TF-IDF, Bag of Words (BoW), dan Cosine Similarity.
- **Named Entity Recognition (NER)**: Mengekstrak entitas penting seperti nama orang, organisasi, dan lokasi dari teks berita.
- **Visualisasi**: Menampilkan hasil analisis sentimen, tren berita, dan word cloud untuk kata-kata yang paling sering muncul.

## Hasil Kuantitatif
- Jumlah artikel yang dianalisis: **5.036**
- Sentimen:
  - Artikel netral: **3.342**
  - Artikel negatif: **1.013**
  - Artikel positif: **680**
- Jumlah cluster yang diidentifikasi:
  - Cluster 0: **1.243 dokumen**
  - Cluster 1: **858 dokumen**
  - Cluster 2: **2.934 dokumen**
- Total entitas yang terdeteksi melalui NER: **1.028.636**

## Instalasi
Untuk menjalankan proyek ini, Anda perlu menginstal beberapa dependensi. Anda dapat menggunakan pip untuk menginstal pustaka yang diperlukan:

```bash
pip install pandas matplotlib transformers polyglot
pip install icu pycld2 pyicu morfessor
```

## Penggunaan
1. Unduh dataset berita BPJS Kesehatan.
2. Lakukan praproses data untuk membersihkan teks.
3. Terapkan analisis sentimen menggunakan metode yang telah ditentukan.
4. Lakukan clustering pada data berita.
5. Jalankan NER untuk mengekstrak entitas penting dari teks.
6. Visualisasikan hasil analisis dengan grafik dan word cloud.

## Kontribusi
Kontribusi terhadap proyek ini sangat diterima! Jika Anda memiliki saran atau perbaikan, silakan buat pull request atau buka isu di repositori ini.

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](LICENSE).

