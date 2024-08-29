# Ide Seru di Balik Proyek Ini 🚗💸

Proyek ini tercetus dari sebuah berita menarik yang menyebutkan kalau ada pola unik pada angka depan pelat nomor kendaraan! Ternyata, jika sebuah mobil dibeli tunai, angka depan pelat nomornya sering kali adalah 2. Begitu juga dengan motor—jika dibeli tunai, angka depan pelatnya biasanya 4 atau 6.

Nah, kalau kendaraan dibeli dengan kredit, angka depannya bisa 1, 3, 5, 7, 8, atau 9! Seru, kan? Dari situ muncul ide untuk membuat sebuah sistem yang bisa mengenali pola ini dan otomatis mendeteksi apakah sebuah kendaraan dibeli tunai atau kredit, hanya dari angka depan pelat nomornya. 🎉

# Dataset

Karena terinspirasi oleh ide tersebut, langsung dilakukan pencarian dataset pelat nomor dari berbagai sumber eksternal. Tujuannya? Tentu saja untuk menguji dan mengembangkan sistem yang bisa mendeteksi pelat nomor, baik untuk mobil, motor, maupun kendaraan jenis lainnya. Dengan dataset ini, bisa mulai bereksperimen dan melihat seberapa akurat sistem dalam mengenali dan mengklasifikasikan pelat nomor sesuai dengan pola pembayaran yang dipikirkan. 🚗🔍

Dataset yang digunakan pada project ini:

https://universe.roboflow.com/marcin-brzeaski/anpr-wpigd/

# Integrasi OCR

Setelah menemukan model yang cocok, yaitu menggunakan YoloV7, rencana berikutnya adalah melakukan integrasi dengan EasyOCR. Mengapa memilih EasyOCR dibandingkan OCR open source lainnya seperti Tesseract, docTR, atau keras-OCR? Karena EasyOCR memiliki tingkat akurasi yang lebih tinggi serta pemrosesan pembacaan yang lebih efisien, menjadikannya pilihan terbaik untuk proyek ini.

# Improvement

Hasil dari model ini sudah cukup memuaskan untuk kasus deteksi pelat nomor pada mobil. Namun, untuk meningkatkan akurasi deteksi pada motor, diperlukan tambahan dataset khusus. Update ini akan menjadi fokus pengembangan berikutnya. 🚀
