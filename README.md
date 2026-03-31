# Financial Transaction Analysis: Clustering & Classification 🚀

Proyek ini bertujuan untuk menganalisis perilaku transaksi keuangan nasabah menggunakan teknik Machine Learning. Dengan menggabungkan metode *Unsupervised Learning* (Clustering) dan *Supervised Learning* (Classification), proyek ini mampu mengidentifikasi segmen nasabah dan memprediksi kategori transaksi secara otomatis.

## 📊 Business Understanding
Dalam dunia fintech, memahami pola transaksi sangat penting untuk:
- Segmentasi nasabah (Customer Segmentation).
- Deteksi dini aktivitas anomali atau penipuan (Fraud Detection).
- Personalisasi layanan keuangan berdasarkan perilaku belanja.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Yellowbrick.
- **Tools:** Google Colab, GitHub.

## ⚙️ Workflow & Methods
1. **Exploratory Data Analysis (EDA):** Meninjau statistik data dan menangani *missing values*.
2. **Preprocessing:** Melakukan standarisasi data menggunakan `StandardScaler` dan *encoding* pada fitur kategorikal.
3. **Clustering (K-Means):** - Menentukan jumlah klaster optimal menggunakan **Elbow Method**.
   - Melatih model untuk mengelompokkan data transaksi ke dalam beberapa kategori.
4. **Evaluasi Clustering:** - **Silhouette Score:** ~0.34
   - **Davies-Bouldin Index:** ~0.95 (Menunjukkan pemisahan klaster yang cukup solid).
5. **Classification:** Membangun model klasifikasi berdasarkan label yang dihasilkan dari proses clustering.

## 📈 Key Results
Hasil analisis menunjukkan adanya pola unik pada durasi transaksi dan saldo akun yang membedakan setiap kelompok nasabah. Model klasifikasi yang dibangun dapat membantu operasional perbankan dalam mengkategorikan transaksi baru secara real-time.

---
*Proyek ini merupakan bagian dari Submission Akhir Belajar Machine Learning Terapan (BMLP).*
