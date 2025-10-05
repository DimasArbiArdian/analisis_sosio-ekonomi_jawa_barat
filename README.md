# Analisis Sosio-Ekonomi Jawa Barat (2020–2022)

## 📘 Project Overview
Proyek ini bertujuan untuk menganalisis kondisi sosio-ekonomi di Provinsi Jawa Barat dalam periode 2020–2022. Fokus utama analisis adalah pada tiga indikator utama kesejahteraan masyarakat, yaitu:
- **Indeks Pembangunan Manusia (IPM)** sebagai indikator kualitas hidup.
- **Tingkat Kemiskinan** sebagai indikator kesejahteraan ekonomi.
- **Rasio Gini** sebagai indikator ketimpangan pendapatan.

Dengan menggabungkan ketiga indikator ini, proyek ini mencoba mengidentifikasi tren, hubungan antar variabel, serta daerah yang membutuhkan perhatian khusus dari pembuat kebijakan.

## 🧩 Raw Datasets
1. [IPM Jawa Barat (2020–2022)](./ipm_awa_barat(2020-2022).csv)
2. [Kemiskinan Jawa Barat (2020–2022)](./kemiskinan_jawa_barat(2020-2022).csv)
3. [Rasio Gini Jawa Barat (2020–2022)](./rasio_gini_jawa_barat(2020-2022).csv)

Sumber data diambil dari **Badan Pusat Statistik (BPS) Jawa Barat**.

## 🧠 Analysis Process
1. **Data Collection:** Mengimpor tiga dataset dan membersihkan data (missing value, format angka, dsb).  
2. **Data Merging:** Menggabungkan dataset berdasarkan kolom *Kabupaten/Kota* dan *Tahun*.  
3. **Exploratory Data Analysis (EDA):**
   - Analisis tren IPM, kemiskinan, dan rasio gini per tahun.
   - Analisis korelasi antar indikator.
   - Visualisasi menggunakan grafik garis dan scatter plot.  
4. **Findings Interpretation:** Menarik insight dari hasil visualisasi dan perhitungan statistik.  
5. **Recommendations:** Memberikan rekomendasi kebijakan untuk perbaikan kesejahteraan sosial.

## 📊 Insights & Findings
- **IPM meningkat** di hampir seluruh wilayah Jawa Barat dari 2020–2022, menunjukkan peningkatan kualitas hidup.
- **Tingkat kemiskinan menurun**, namun penurunan tidak merata di seluruh kabupaten.
- **Rasio Gini relatif stabil**, menunjukkan ketimpangan pendapatan belum banyak berubah.
- Terdapat **korelasi negatif antara IPM dan kemiskinan**, artinya daerah dengan IPM tinggi cenderung memiliki tingkat kemiskinan lebih rendah.

## 💡 Conclusion & Recommendations
- Fokus kebijakan perlu diarahkan pada daerah dengan IPM rendah dan tingkat kemiskinan tinggi seperti beberapa kabupaten di bagian selatan Jawa Barat.
- Peningkatan akses pendidikan dan lapangan kerja dapat membantu menurunkan kemiskinan dan meningkatkan IPM.
- Ketimpangan ekonomi perlu dikurangi melalui pemerataan pembangunan dan dukungan terhadap UMKM.

## 🤖 AI Support Explanation
Proyek ini menggunakan bantuan **AI generatif (IBM Granite / GPT Model)** untuk:
- **Klasifikasi dan ringkasan data** hasil analisis.
- **Interpretasi insight** dari hasil EDA.
- **Pembuatan dokumentasi (README & presentasi)** secara otomatis berdasarkan data notebook.

## 🧪 Tools & Environment
- **Google Colab** (Python 3, Pandas, Matplotlib, Seaborn)
- **IBM Granite LLM** / ChatGPT untuk summarization
- **Dataset Excel dari BPS Jawa Barat**

## 📎 Author
**Dimas Arbi Ardian**  
Capstone Project – IBM Student Development Initiative
