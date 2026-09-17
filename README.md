# Sentiment Analysis NLP dengan Streamlit

Aplikasi web sederhana menggunakan Streamlit untuk melakukan analisis sentimen pada teks Bahasa Inggris dan Bahasa Indonesia.

## Fitur

- Analisis sentimen Bahasa Inggris menggunakan TextBlob dan VADER
- Analisis sentimen Bahasa Indonesia menggunakan Indonesia BERT
- Menampilkan hasil sentiment dan confidence
- Menampilkan hasil analisis dalam bentuk tabel
- Menampilkan visualisasi hasil analisis
- Analisis sentimen setiap kata

## Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- Altair
- TextBlob
- VADER
- Transformers
- Indonesia BERT

## Cara Menjalankan

Install library yang dibutuhkan:
pip install -r requirements.txt

Jalankan analisis Bahasa Inggris:
streamlit run sentiment_inggris.py

Jalankan analisis Bahasa Indonesia:
streamlit run sentiment_indonesia.py

## Model Bahasa Indonesia

Model yang digunakan:
mdhugol/indonesia-bert-sentiment-classification
