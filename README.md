🧠 Langkah-Langkah Pengerjaan Proyek Klasifikasi Tingkat Stres
🔍 Identifikasi Masalah & Tujuan
Menentukan fokus pada klasifikasi stres dan depresi, serta menetapkan tujuan untuk mengukur performa algoritma KNN pada dua jenis data.

📚 Studi Literatur
Menelaah artikel penelitian sebelumnya untuk memahami metode, hasil, dan keterbatasan, khususnya yang membandingkan KNN dan Naïve Bayes.

📥 Pengumpulan Dataset
Mengambil dataset dari Kaggle: Depression Professional Dataset sebagai data utama untuk analisis.

🧹 Preprocessing Data

Menghapus nilai kosong dan data duplikat.

Normalisasi & encoding atribut.

Menyeimbangkan data menggunakan SMOTE ⚖️.

🧪 Pembagian Data

Data latih: 80% 🧠

Data uji: 20% 📊
Tujuannya agar model diuji pada data yang belum pernah dilihat.

🤖 Pembuatan Model KNN

Membangun model klasifikasi menggunakan KNN.

Menentukan nilai k terbaik dengan GridSearchCV 🔧.

📈 Evaluasi Model
Menggunakan metrik evaluasi seperti:

✅ Accuracy

🎯 Precision

🔍 Recall

⚖️ F1-Score

📉 ROC AUC
Disertai visualisasi Confusion Matrix & Heatmap.

🧾 Interpretasi Hasil
Menganalisis performa model, mengidentifikasi kekuatan & kelemahan, serta membandingkan dengan hasil dari artikel penelitian.

📝 Kesimpulan & Saran
Menyimpulkan hasil akhir eksperimen dan memberikan saran seperti peningkatan jumlah data dan eksplorasi algoritma lain untuk klasifikasi yang lebih akurat.
