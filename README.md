# Netflix Reviews Sentiment Analysis Using Granite LLM

---

## 🎯 Tujuan Proyek

- Menentukan sentimen dari review Netflix (Positif, Negatif, Campur)  
- Mengetahui titik kelebihan / kekurangan Netflix dari Review (UI/UX, Content, Performance, etc.)  
- Memberikan rekomendasi / kesimpulan untuk perbaikan sistem Netflix  

---

## 🔍 Latar Belakang Proyek

Saat ini, banyak aplikasi yang menyaingi Netflix, mulai dari Disney+, Prime, Video, WeTV, dll. Oleh karena itu, Netflix harus bisa menyaingi aplikasi lainnya, dengan cara mengembangkan fitur positifnya dan memperbaiki fitur yang kurang sesuai dengan review usernya.

---

## ❓ Permasalahan Spesifik

- Apakah sentimen user cenderung positif, negatif, atau campuran?  
- Apa kategori fitur yang paling sering menjadi masalah?  
- Fitur atau aspek mana yang paling disukai oleh user?  

---

## 🧪 Metode Penelitian

1. Kumpulan Data Review  
2. Mengelola data (Pre-Processing sederhana, cth. hapus spam, hapus yang NaN)  
3. Analisis Sentimen dengan LLM (Granite):
   - Mengklasifikasikan review ke dalam sentimen: Positif, Negatif, atau Campuran.
   - Mengidentifikasi kategori keluhan seperti: Performance, UX/UI, Fitur, Bug, dan sebagainya.
   - Mengelompokkan hasil untuk mendapatkan insight keseluruhan
4. Visualisasi data dengan grafik  
5. Menyusun rekomendasi konkret berdasarkan insight yang ditemukan.

---

## Dataset
[Netflix Reviews - Kaggle](https://www.kaggle.com/datasets/ashishkumarak/netflix-reviews-playstore-daily-updated/code)

---

## 📊 Insight

### Kekurangan Netflix:
- **Dominan Masalah Teknis** (Bugs 7 reviews, Performance 5 reviews)  
- User mengalami aplikasi yang sering keluar sendiri, tidak bisa log in, buffering lama, serta rendahnya stabilitas aplikasi.  
- Beberapa user juga merasakan bahwa harga dari Netflix terlalu tinggi, hal tersebut juga bisa dipengaruhi oleh kualitas performa aplikasi yang masih jauh dari yang diharapkan penggunanya.  
- UI/UX juga mendapatkan komplain, mulai dari notifikasi yang berlebih hingga perbedaan tampilan pada IOS dan Android.  
- **Security**, yang masih harus ditingkatkan, karena adanya kasus peretasan akun pengguna.  

Oleh karena itu, dapat terbilang, sentimen negatif sedikit lebih banyak daripada yang positif, dimana sentimen negatif 1 lebih banyak daripada positif. Salah satu aspek yang paling dirasa kurang adalah banyaknya bugs dan performa aplikasi yang kurang, apalagi aplikasi ini berbayar.  

### Kelebihan Netflix:
- **Isi Konten**  
  - User merasa cukup puas dengan isi konten yang ada, 7 dari 25 reviewer memberikan sentimen positif karena adanya konten yang berkualitas.  
  - Beberapa pengguna juga menyampaikan bahwa kontennya sangat bervariasi / luas, mulai dari film hingga berbagai acara TV.  
  - Mereka juga puas karena kualitas video yang sangat baik.  
  - Minoritas juga menyampaikan adanya sisi positif pada UI/UX-nya dan juga kenyamanan karena user bisa menonton video ketika offline.  

Meskipun review sentimen positif hanya berbeda satu dengan yang negatif, akan tetapi bisa dibilang Netflix masih memiliki sangat buruk dari penilaian penggunanya, karena dari sisi positifnya hanya ada 1 yang bisa menjadi unggulan yakni keberagaman dan kualitas konten.

---

## ✅ Conclusion

Berdasarkan analisis 25 review pengguna, Netflix memiliki kelebihan utama pada kualitas dan keberagaman konten yang ditawarkan, termasuk film dan acara TV yang menarik dengan video berkualitas tinggi. Sebagian kecil pengguna juga mengapresiasi fitur offline viewing serta desain antarmuka yang nyaman.  
Namun, sentimen negatif sedikit lebih dominan dibandingkan positif. Kritik paling banyak muncul terkait masalah teknis seperti bug (7 review), performa buruk (5 review), aplikasi sering keluar sendiri, login gagal, buffering, dan rendahnya stabilitas.  
Selain itu, harga dianggap terlalu mahal jika dibandingkan dengan kualitas teknis aplikasi. Masalah lain termasuk UI/UX yang inkonsisten antara iOS dan Android, notifikasi berlebih, serta isu keamanan akun (security) akibat adanya kasus peretasan.

---

## 💡 Recommendations

- Perbaiki performa dan stabilitas aplikasi secara menyeluruh di semua platform, agar pengguna berbayar merasa puas dengan kualitas layanan.  
- Optimalkan UI/UX agar konsisten di seluruh sistem operasi (iOS & Android) serta mengurangi notifikasi yang mengganggu.  
- Tingkatkan sistem keamanan akun, termasuk notifikasi login mencurigakan dan autentikasi ganda (2FA), untuk menghindari peretasan.  
- Pertimbangkan penyesuaian harga atau pemberian nilai tambah (misalnya bonus akses konten tertentu) untuk menyeimbangkan dengan performa teknis saat ini.  
- Fokuskan pemasaran pada kekuatan utama Netflix, yaitu keberagaman konten dan kualitas video, sambil terus memperbaiki aspek teknis yang menjadi keluhan utama.  

Dengan begitu, diharapkan user Netflix dapat lebih nyaman ketika menggunakan aplikasi, dan tidak berpindah ke aplikasi streaming lainnya. Selain itu, sentimen negatif dari review bisa berkurang seiring bertambahnya sentimen positif.

---

## 🤖 AI Support Explanation

Granite sangat membantu analisis sentimen review untuk user Netflix. Hal tersebut dikarenakan Granite mampu memahami konteks bahasa manusia dengan mendalam, bahkan sentimen seperti negatif, positif, maupun campuran. Model ini juga bisa mengklasifikasikan topik yang sedang diulas, mulai dari isi konten, performa, fitur, harga dll.  
Oleh karena itu, Granite dapat menganalisa sentimen jauh lebih cepat jika dibandingkan manual, hal tersebut terlihat ketika Summary Granite memiliki hasil relatif mirip dengan visualisasi data dari Klasifikasi Sentimen. Dengan begitu, dapat dikatakan bahwa Granite sangat cocok untuk memproses ratusan review dalam waktu yang singkat, serta scaleable.  
Granite juga bisa memberikan insight yang mendalam bagi tim produksi dari Netflix, untuk mengetahui titik lemah / kelebihan dari Netflix.

