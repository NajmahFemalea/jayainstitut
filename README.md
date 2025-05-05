# Proyek Akhir: Menyelesaikan Permasalahan Pendidikan Jaya Jaya Institut



## Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout.

### Permasalahan Bisnis
Jaya Jaya Institut ingin mendeteksi secepat mungkin siswa yang mungkin akan melakukan dropout sehingga dapat diberi bimbingan khusus. 

### Cakupan Proyek
Proyek ini bertujuan untuk membantu Jaya Jaya Institut dalam mengidentifikasi siswa yang berisiko tinggi mengalami dropout melalui pendekatan data science. Tahapan proyek dimulai dari proses akuisisi dan pembersihan data, dilanjutkan dengan eksplorasi data untuk memahami pola-pola penting yang berkaitan dengan performa siswa. Kemudian dilakukan proses feature engineering dan seleksi fitur untuk menentukan variabel yang paling relevan dalam memprediksi risiko dropout. Setelah itu, dibangun model klasifikasi menggunakan algoritma machine learning seperti Decision Tree, Random Forest, dan Gradient Boosting untuk memprediksi kemungkinan siswa akan dropout. Selain itu, proyek ini juga mencakup pembuatan dashboard interaktif yang membantu tim akademik memonitor performa siswa secara visual, serta pengembangan prototype aplikasi prediksi berbasis Streamlit yang dapat digunakan untuk memasukkan data siswa baru dan memperoleh hasil prediksi secara langsung.

### Persiapan

Sumber data: [Students' Academic Performance](https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv)

Setup environment:

**Clone Repo**
```
git clone https://github.com/NajmahFemalea/jayainstitut.git
cd jayainstitut
```
**Setup Virtual Environment (opsional)**
```
python3 -m venv venv
.\venv\Scripts\activate         
```
**Setup**
```
pip install -r requirements.txt
```

## Business Dashboard
Jelaskan tentang business dashboard yang telah dibuat. Jika ada, sertakan juga link untuk mengakses dashboard tersebut.

## Menjalankan Sistem Machine Learning
Link: []()<br>
run on local:
```
streamlit run student_performance_app.py
```

## Conclusion
Jelaskan konklusi dari proyek yang dikerjakan.

### Rekomendasi Action Items
Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.
- action item 1
- action item 2
