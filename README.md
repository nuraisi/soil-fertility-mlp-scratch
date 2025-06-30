# Klasifikasi Tingkat Kesuburan Tanah Menggunakan  Algoritma Multi Layer Perceptron Backpropagation

Proyek ini bertujuan untuk mengklasifikasikan tingkat kesuburan tanah berdasarkan parameter kimia dan unsur hara menggunakan algoritma Multi Layer Perceptron (MLP) dengan metode backpropagation. Model dikembangkan dari nol (from scratch) tanpa menggunakan library machine learning seperti scikit-learn atau TensorFlow, untuk memperdalam pemahaman terhadap konsep fundamental jaringan saraf tiruan dan proses pelatihan berbasis propagasi error. Proyek ini dibuat sebagai eksplorasi praktis dalam membangun arsitektur neural network sendiri, serta untuk mengidentifikasi tingkat kesuburan tanah secara otomatis guna mendukung praktik pertanian yang lebih efisien dan berbasis data.

Dataset ini berisi informasi seperti:

- N
- P
- pH
- EC
- dll 

Pendekatan dan langkah-langkah utama:
1. Menyiapkan dataset yang berisi fitur-fitur kimia tanah dan unsur hara.
2. Melakukan normalisasi data agar sesuai untuk input jaringan saraf.
3. Mendesain arsitektur MLP (jumlah input, hidden layer, dan output).
4. Mengimplementasikan fungsi aktivasi, propagasi maju (forward), dan propagasi balik (backpropagation) secara manual.
5. Melatih model menggunakan iterasi epoch dan menghitung loss secara berkala.
6. Mengukur akurasi dan mengevaluasi hasil klasifikasi tingkat kesuburan tanah.
