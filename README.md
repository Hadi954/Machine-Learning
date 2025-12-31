#  README – Ringkasan Proyek Machine Learning

**Nama Mahasiswa** : Mohammad Hadi Purnomo  
**NIM**            : 231011402465  
**Kelas**          : 05TPLP001  
**Mata Kuliah**    : Machine Learning  
**Proyek**         : Ujian Akhir Semester (UAS)  

---

##  Ringkasan Masalah
Polusi udara merupakan permasalahan lingkungan yang berdampak langsung terhadap kesehatan manusia. Salah satu gas berbahaya yang sering muncul di wilayah perkotaan adalah karbon monoksida (CO). Oleh karena itu, diperlukan pendekatan berbasis data untuk memprediksi konsentrasi CO menggunakan informasi dari sensor kualitas udara dan faktor lingkungan.

Proyek ini bertujuan untuk membangun model machine learning yang mampu memprediksi konsentrasi karbon monoksida (CO) berdasarkan data kualitas udara.

---

##  Model yang Digunakan
Model utama yang digunakan dalam proyek ini adalah **Random Forest Regressor**.  
Model ini dipilih karena:
- Mampu menangani hubungan non-linear antar variabel
- Lebih robust terhadap noise
- Menyediakan informasi **feature importance** untuk interpretasi model

---

##  Hasil Utama
- Model Random Forest Regressor mampu memprediksi konsentrasi CO dengan performa yang baik.
- Evaluasi menggunakan metrik regresi (MAE, RMSE, dan R²) menunjukkan error yang relatif rendah.
- Visualisasi aktual vs prediksi memperlihatkan bahwa hasil prediksi mengikuti pola data aktual.

---

##  Insight / Temuan Penting
- Sensor gas seperti **C6H6(GT)** dan **PT08.S2(NMHC)** memiliki pengaruh paling besar dalam memprediksi konsentrasi CO.
- Faktor lingkungan seperti suhu dan kelembaban berperan sebagai variabel pendukung.
- Pendekatan machine learning terbukti efektif untuk mendukung sistem pemantauan dan prediksi kualitas udara.

---

 *Notebook ini disusun sebagai bagian dari Ujian Akhir Semester (UAS) pada mata kuliah Machine Learning.*
