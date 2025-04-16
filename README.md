# 🏃‍♀️ RunningApp-SentimentAnalysis

Selamat datang di proyek **Running App Sentiment Analysis**!  
Proyek ini bertujuan untuk menganalisis sentimen dari ulasan pengguna aplikasi **Running App** yang tersedia di Google Play Store. Data dikumpulkan melalui proses scraping, dibersihkan, dianalisis, dan digunakan untuk membangun model klasifikasi sentimen.

📁 **Struktur Notebook Proyek**  
Proyek ini dibagi ke dalam 4 tahapan utama yang masing-masing direpresentasikan oleh 4 notebook:

---

### 📌 `1_Scrapping_Apps_Running.ipynb`  
Tahap ini bertujuan untuk mengumpulkan data review pengguna dari Google Play Store menggunakan teknik **web scraping**. Hasilnya berupa dataset mentah yang siap diproses lebih lanjut.

---

### 🧹 `2_Preprocessing_Apps_Running.ipynb`  
Notebook ini berfokus pada **pembersihan dan normalisasi teks**, seperti:
- Menghapus karakter khusus
- Mengubah huruf menjadi lowercase
- Tokenisasi dan stopword removal
- Lemmatization, dst

---

### 📊 `3_EDA_Apps_Running.ipynb`  
Tahapan **Exploratory Data Analysis (EDA)** dilakukan untuk memahami pola dan karakteristik data, seperti:
- Distribusi sentimen
- Frekuensi kata/kalimat umum
- Wordcloud dan visualisasi statistik lainnya

---

### 🧠 `4_Feature_Engineering_and_Classification_Apps_Running.ipynb`  
Notebook ini mencakup dua bagian utama:
1. **Feature Engineering**
2. **Modeling & Classification**:
   - Membangun dan mengevaluasi beberapa model klasifikasi seperti:
     - Linear SVM
     - Logistic Regression
     - Naive Bayes
     - XGBoost
     - Random Forest

---

Dengan alur ini, proyek bertujuan memberikan insight berharga dari opini pengguna guna mendukung pengembangan fitur dan kualitas aplikasi Running App.

✨ Happy Analyzing!
