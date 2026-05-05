
# Analisis Sentimen Mobile JKN

Project ini berisi analisis sentimen komentar pengguna aplikasi Mobile JKN dari Google Play Store.

## Dataset

Data diperoleh menggunakan library `google-play-scraper`.

Jumlah data: 1000 komentar.

## Kolom Dataset

- `userName`: nama pengguna
- `score`: rating pengguna
- `at`: tanggal ulasan
- `content`: isi komentar
- `sentimen`: hasil klasifikasi sentimen
- `confidence`: tingkat keyakinan model

## Model

Analisis sentimen menggunakan model:

`w11wo/indonesian-roberta-base-sentiment-classifier`

Model ini mengklasifikasikan komentar menjadi:
- positive
- negative
- neutral

## Tools

- Google Colab
- Python
- Pandas
- Transformers
- Torch
- Matplotlib
- Google Play Scraper
