Social-Networks-Ads
Logistic Regression
Regresi logistik adalah algoritma klasifikasi yang digunakan untuk menetapkan observasi ke sekumpulan kelas diskrit. Tidak seperti regresi linier yang mengeluarkan nilai bilangan kontinu, regresi logistik mengubah keluarannya menggunakan fungsi sigmoid logistik untuk mengembalikan nilai probabilitas yang kemudian dapat dipetakan ke dua atau lebih kelas diskrit.

untuk lebih lanjut - https://ml-cheatsheet.readthedocs.io/en/latest/logistic_regress.html

K Nearest Neighbors
Representasi model untuk KNN adalah seluruh dataset pelatihan.

Sesederhana itu.

KNN tidak memiliki model selain menyimpan seluruh dataset, jadi tidak diperlukan pembelajaran.

Implementasi yang efisien dapat menyimpan data menggunakan struktur data yang kompleks seperti pohon kd untuk membuat pencarian dan pencocokan pola baru selama prediksi menjadi efisien.

Karena seluruh set data pelatihan disimpan, Anda mungkin ingin memikirkan dengan cermat tentang konsistensi data pelatihan Anda. Sebaiknya kurasi, perbarui sesering mungkin saat data baru tersedia, dan hapus data yang salah dan outlier mungkin merupakan ide yang bagus.

KNN bekerja dengan baik dengan sejumlah kecil variabel input (p), tetapi kesulitan ketika jumlah input sangat besar.

Set data dapat diunduh dari - https://www.kaggle.com/rakeshrau/social-network-ads#Social_Network_Ads.csv

Tujuan kami adalah untuk memprediksi apakah seseorang akan dapat membeli mobil tergantung pada usia dan gajinya
Dengan menggunakan Regresi Logistik kami memperoleh akurasi sebesar - 0,875

Dengan menggunakan K Tetangga Terdekat, kami memperoleh akurasi - 0,9166666666666666
