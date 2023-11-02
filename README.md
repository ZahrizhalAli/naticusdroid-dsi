# 🚀 Data Science Playground Competition - NATICUSdroid by Data Science Indonesia

### 🔍 Deskripsi Permasalahan
Pesatnya pertumbuhan aplikasi Android dan popularitasnya di pasar ponsel pintar global telah menjadikannya target malware yang mudah dan dapat diakses. Dalam beberapa tahun terakhir, sistem operasi Android (AOS) telah beberapa kali diperbarui untuk mengatasi berbagai kerentanan. Sayangnya, aplikasi malware juga berevolusi dan disesuaikan dengan perkembangan tersebut.
Memang, kebutuhan deteksi malware untuk Android sangat penting dalam menginvestigasi dan mengklasifikasikan aplikasi sebagai jinak (tidak berbahaya) atau malware (berbahaya). Dengan sifat malware yang terus berkembang, penting untuk memiliki mekanisme deteksi yang kuat dan terkini untuk melindungi pengguna dari potensi risiko keamanan.
Dengan terus meningkatkan dan menyempurnakan metode deteksi ini, pengembang dan pakar keamanan dapat melindungi pengguna Android dengan lebih baik dari potensi ancaman yang ditimbulkan oleh aplikasi yang terinfeksi malware. Deteksi malware yang tepat waktu dan efektif merupakan aspek penting dalam menjaga keamanan dan integritas ekosistem Android.
Dari permasalahan ini, kamu harus menentukan pola dari malware dengan data yang tersedia serta membuat model untuk memprediksi adanya kemungkinan malware di aplikasi.

### 📝 Methods
* Data Preparation
* Exploratory Data Analysis
* Modelling
* Evaluasi Model
* Kesimpulan dan Rekomendasi

### ⚙ Tech Used
* Python 3.11
* TensorFlow
* Scikit Learn
* Pandas
* Matplotlib dan Seaborn

### Data Preparation
Data berisi izin yang diambil dari lebih dari 29.000 aplikasi Android, termasuk aplikasi jinak (tidak berbahaya) dan malware (berbahaya). Aplikasi ini dirilis antara tahun 2010 dan 2019.

* Jumlah data train: 20531 data
* Jumlah data test: 8799 data
* Jumlah column data Train 88
* Jumlah column data Test 87

### Exploratory Data Analysis
Benign vs Malware

![image](https://github.com/ZahrizhalAli/naticusdroid-dsi/assets/58893316/066574c5-e59a-4cde-90d9-1d01ca6d843c)

### Model Experiments
1. Random Forest with KFold
2. Random Forest with GridSearch
3. Support Vector Classifier using Polynomial Kernel
4. Ensemble Model (RF, SVC, AdaBoost, DecisionTree)
5. AdaBoost (Boosting Method)
6. Deep Learning (Dense)

### Model Evaluation

#### Confusion Matrix - Model Voting Classifier (Ensemble)
![image](https://github.com/ZahrizhalAli/naticusdroid-dsi/assets/58893316/ea6de6f2-a579-4ab9-b008-1b9277f136ae)

#### ROC (Receiver Operating Characteristics) 
![image](https://github.com/ZahrizhalAli/naticusdroid-dsi/assets/58893316/b0bd6e18-eeb7-49a1-8908-5b1cfedacd70)


