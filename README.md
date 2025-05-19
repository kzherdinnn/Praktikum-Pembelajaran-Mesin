# 🧠 Sentiment Analysis using SVM

## 📌 Deskripsi Proyek

Proyek ini merupakan implementasi sederhana dari _Sentiment Analysis_ (analisis sentimen) menggunakan algoritma **Support Vector Machine (SVM)**. Dataset yang digunakan terdiri dari teks berlabel sentimen **positif** dan **negatif**. Proyek ini mengacu pada repository GitHub berikut:

🔗 [Referensi GitHub - Jatin Warade](https://github.com/jatinwarade/Sentiment-analysis-using-SVM)

## 🗂️ Struktur File

```bash
SENTIMENT-ANALYSIS-USING-SVM/
├── .ipynb_checkpoints/
│   └── SVM-checkpoint.ipynb
├── README.md
├── SVM.ipynb              # Notebook utama berisi kode program
├── Training.txt           # Dataset latih

## ⚙️ Langkah-langkah Proses

1. **Load Dataset**
   - Membaca data dari file `Training.txt`.

2. **Preprocessing**
   - Mengubah ke lowercase
   - Tokenisasi
   - Menghapus stopwords

3. **Ekstraksi Fitur**
   - Menggunakan `CountVectorizer` untuk mengubah teks menjadi vektor numerik.

4. **Training Model**
   - Melatih model klasifikasi menggunakan `sklearn.svm.SVC`.

5. **Evaluasi**
   - Mengukur akurasi
   - Menampilkan confusion matrix dan classification report

## 🧪 Contoh Output

```plaintext
Accuracy: 0.92

Confusion Matrix:
[[45  3]
 [ 5 47]]

## ✅ Kesimpulan

Algoritma **SVM** cukup efektif untuk klasifikasi sentimen teks pendek. Dengan *preprocessing* sederhana dan fitur berbasis kata, model ini mampu mencapai akurasi yang tinggi.

Proyek ini bisa dikembangkan lebih lanjut dengan:
- Menggunakan dataset yang lebih besar
- Mengganti metode ekstraksi fitur dengan **TF-IDF**
- Menerapkan representasi teks lanjutan seperti **Word Embeddings** (*Word2Vec*, *GloVe*, dll)

> SVM merupakan algoritma yang andal untuk klasifikasi teks sederhana dan tetap relevan untuk tugas-tugas NLP dasar.

