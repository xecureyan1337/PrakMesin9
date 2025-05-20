# 💬 Sentiment Analysis using SVM

Proyek ini merupakan implementasi sederhana dari Analisis Sentimen menggunakan algoritma Support Vector Machine (SVM). Tujuan utama dari proyek ini adalah untuk mengklasifikasikan teks ulasan (review) ke dalam sentimen positif atau negatif berdasarkan fitur yang diekstraksi dari data teks.

# 📌 Fitur Utama
- Preprocessing teks: case folding, stopword removal, stemming.
- Ekstraksi fitur menggunakan TF-IDF.
- Pelatihan model klasifikasi dengan SVM (Support Vector Machine).
- Evaluasi model menggunakan akurasi dan confusion matrix.
- Visualisasi hasil evaluasi

# 🧠 Algoritma
- SVM (Support Vector Machine) digunakan karena kemampuannya menangani data teks berdimensi tinggi dengan baik.
- Kernel yang digunakan: linear (default)

# 📈 Evaluasi
- Akurasi
- Precision, Recall, F1-scoren
- Confusion Matrix

# 🗿 Predicted Label with SVM
![image](https://github.com/user-attachments/assets/ca4f7d93-c179-4d66-adc7-1c2fc89d5b17)

> Hasil prediksi model mengatakan bahwa True Positive dan True Negative memiliki nilai yang besar, yang artinya model memprediksi terdapat ulasan positif dan negatif walaupun ulasan negatif lebih banyak daripada positif yang memiliki nilai 809 > 568. Disisi lain, ada pula False Positive dan False Negative yang nilainya bisa dihitung jari...

# 📚 Teknologi & Library
- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas
- NLTK
- Matplotlib

# 🔮 Pengembangan Selanjutnya
- 🤖 Tambahkan model pembanding (Naive Bayes, Random Forest, LSTM)
- 🌐 Deploy menggunakan Streamlit atau Flask
- 📱 Buat API untuk klasifikasi real-time

<p align="center"> <img src="https://user-images.githubusercontent.com/7091227/224471288-3704b780-3fc0-11ed-8cf2-3c991cd58dc3.gif" width="300px" /> </p> <p align="center"><b>Happy Coding & Keep Learning! 🚀</b></p>
