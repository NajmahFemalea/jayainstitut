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
Link: [Students Performance Dashboard](https://public.tableau.com/app/profile/najmah.femalea/viz/StudentsPerformance_17466285039170/StudentsPerformance)

Dashboard menampilkan ringkasan dan visualisasi komprehensif mengenai status akademik dan keuangan siswa. Di bagian atas terlihat jumlah mahasiswa yang dropout (1.421), masih terdaftar/enrolled (794), dan yang telah lulus/graduate (2.209), beserta tingkat dropout sebesar 32,12 %. Selanjutnya, grafik “Scholarship Holder vs Non-Holder per Status” memerlihatkan perbandingan mahasiswa penerima beasiswa dan non-penerima beasiswa dalam masing-masing kategori status (dropout, enrolled, graduate). Grafik “Tuition Fees up to Date per Status” menggambarkan jumlah mahasiswa yang membayar biaya kuliah tepat waktu berdasarkan statusnya, sementara grafik “Debtor per Status” menunjukkan jumlah mahasiswa yang masih memiliki tunggakan biaya—juga dikelompokkan menurut status studi. 

## Menjalankan Sistem Machine Learning
Link: []()<br>
run on local:
```
streamlit run student_performance_app.py
```

## Conclusion
Sekitar sepertiga mahasiswa (32 %) tidak menyelesaikan studi mereka, sehingga diperlukan intervensi dini—baik melalui bimbingan akademik maupun dukungan non-akademik—untuk menurunkan angka tersebut. Selain itu, berbagai faktor, seperti kondisi finansial, turut memengaruhi kerentanan putus studi; khususnya, mahasiswa tanpa beasiswa cenderung menghadapi risiko dropout yang lebih tinggi.

### Rekomendasi Action Items
Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.
- Perluas program beasiswa berdasarkan kebutuhan & prestasi
- Reminder otomatis & opsi pembayaran bertahap untuk yang belum up-to-date
- Lakukan case management proaktif: hubungi langsung mahasiswa dengan tunggakan, pahami kendala mereka, dan tawarkan solusi—misalnya perpanjangan waktu atau referral ke departemen keuangan kampus.
- Perkuat layanan student engagement (misalnya klub minat, kegiatan sosial) agar mahasiswa merasa lebih terhubung dengan kampus dan termotivasi menyelesaikan studi
