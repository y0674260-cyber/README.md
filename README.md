
                                                                   PROJECT DATA KELULUSAN MAHASISWA



 1. Deskripsi Dataset 

| Tujuan | Konten yang Diisi | Penjelasan Detail |
| :--- | :--- | :--- |
| **Sumber Data** | datakelulusanmahasiswa.csv | Menunjukkan di mana data tersebut berada (asumsi di folder `/data`). |
| **Kamus Data (Data Dictionary)** | Daftar semua kolom (fitur) yang ada di dataset. |  untuk mencantumkan nama kolom, deskripsi singkatnya, dan tipe datanya (Numerik/Kategorikal). |
| **Fokus Fitur** | Menyoroti fitur-fitur kunci seperti `IPK` dan *target variable* (`STATUS KELULUSAN`). | Berdasarkan data Anda, pastikan semua kolom `IPS 1` hingga `IPS 8`, `IPK`, `UMUR`, dan `STATUS MAHASISWA` tercantum sebagai fitur yang digunakan. |

2. Langkah Pengerjaan 

| Tujuan | Konten yang Diisi | Penjelasan Detail |
| :--- | :--- | :--- |
| **Alur Proyek** | Merangkum langkah-langkah metodologis yang diambil, sesuai dengan pengerjaan di *notebook*. | Gunakan daftar bernomor (1., 2., 3.) agar jelas. Ini adalah peta jalan teknis Anda. |
| **Detail Preprocessing** | Menjelaskan teknik penting yang digunakan. | harus menyebutkan: **a) One-Hot Encoding** (untuk fitur seperti *Jenis Kelamin*, *Status Mahasiswa*), **b) Standard Scaling** (wajib untuk SVM agar performa kernel RBF maksimal), dan **c) Split Data** (membagi menjadi data *Training* dan *Testing*). |
| **Detail Model** | Menjelaskan bagaimana model dibangun. |  menggunakan **Support Vector Machine** dan melakukan **Grid Search CV** untuk mencari *hyperparameter* terbaik (`C` dan `gamma`) untuk Kernel Linear dan RBF. |

 3. Hasil Evaluasi Model 

| Tujuan | Konten yang Diisi | Penjelasan Detail |
| :--- | :--- | :--- |
| **Ringkasan Hasil** | Membandingkan performa model Linear dan RBF. | Ini adalah inti dari *output* proyek . Gunakan **tabel Markdown** untuk membandingkan metrik. |
| **Nilai Aktual** | Nilai Akurasi, Kernel Terbaik, dan *Hyperparameter* terbaik. | ** harus mengganti *placeholder* (`[GANTI DENGAN DATA AKTUAL]`)** dengan angka sebenarnya yang dihasilkan dari *notebook* Anda (misalnya, Akurasi 0.875). |
| **Interpretasi** | Penjelasan mengapa model itu penting dan fitur mana yang paling berpengaruh. | Tulis satu atau dua kalimat yang menjelaskan mengapa model terbaik itu dipilih dan fitur apa (kemungkinan besar IPK) yang memiliki korelasi tertinggi dengan status kelulusan. |

4. Cara Menjalankan Notebook 

| Tujuan | Konten yang Diisi | Penjelasan Detail |
| :--- | :--- | :--- |
| **Replikasi** | Memberikan panduan kepada pembaca (atau penilai) untuk menjalankan ulang kode . | Ini penting untuk memastikan reproduktibilitas. |
| **Prasyarat** | Daftar *library* yang dibutuhkan. | Sebutkan `pandas`, `numpy`, dan `scikit-learn` sebagai *library* utama. |
| **Struktur File** | Menunjukkan lokasi file. | Tunjukkan bahwa file `SVM_kelulusan.ipynb` dan dataset (`datakelulusanmahasiswa.csv`) harus berada di tempat yang benar (dataset di folder `/data`). |
| **Langkah Eksekusi** | Instruksi menjalankan kode. | Cukup instruksikan untuk membuka *notebook* di Jupyter/Colab dan menjalankan semua sel. |


   ## 5. Identitas Mahasiswa

* **Nama:** Yuliana Olo
* **NPM:** 2457201002386
* **Program Studi:** Sistem Informasi (3A)
