### Deskripsi Proyek
Film Junky Union, sebuah komunitas baru bagi penggemar film klasik sedang mengembangkan sistem untuk memfilter dan mengategorikan ulasan film. Misi utamanya adalah melatih model agar bisa mendeteksi ulasan negatif secara otomatis. Anda akan menggunakan *dataset* ulasan film IMBD dengan pelabelan polaritas untuk membuat sebuah model yang bisa mengklasifikasikan ulasan positif dan negatif. Model ini setidaknya harus memiliki skor F1 sebesar 0,85.

### Tujuan
1. Mencari model terbaik dari beberapa model machine learning.
2. Menguji akurasi model terhadap komentar negatif yang diinputkan

### Tahapan
File path: `/datasets/imdb_reviews.tsv`.
1. Tinjauan data
2. Pra-pemrosesan data
3. Evaluasi
4. Normalisasi
5. Pemodelan
6. Pengujian

| Projek | Deskripsi | Modul |
| ------- | ------- | ------- |
| [Analisis Prediksi Komentar Negatif](https://github.com/vikrayudha/Project_TripleTen/blob/main/Project%2014%20-%20Memfilter%20dan%20Mengategorikan%20Ulasan%20Film/Project%2014%20(1).ipynb) | Model prediksi sentimen menggunakan *natural language processing* pada model-model `machine learning`. Tokenisasi dan lematisasi dilakukan menggunakan modul *spaCy*, *nltk*, dan *BERT*. Beberapa `model` yang diujikan `dummy classifier`, `logistic regression` dan `lightGBM`. | *pandas*, *numpy*, *sklearn*, *matplotlib*, *seaborn*, *math*, *re*, *tqdm*, *nltk*, *spaCy*, *LightGBM*, *torch*, *transformers* |

