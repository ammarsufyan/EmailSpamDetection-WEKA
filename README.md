# Spam Detection Using Weka

<h2>Rumusan Masalah</h2>
Setiap hari pengguna email menerima ratusan spam dari alamat baru yang secara otomatis dihasilkan oleh robot pengirim email. Untuk menyaring spam dengan metode tradisional, seperti whitelist hampir tidak mungkin. Penerapan metode text mining pada email dapat meningkatkan efisiensi penyaringan spam.

<h2>Tujuan Penelitian</h2>
Untuk memeriksa bahwa email yang diterima adalah spam atau ham melalui klasifikasi teks di WEKA menggunakan algoritma J48 Decision Tree dan Naive Bayes Multinomial Text. Email spam adalah email yang kita inginkan untuk diterima, sedangkan email ham adalah email yang tidak kita inginkan untuk diterima.

<h2>Dataset</h2>

<b>Source: </b><a href="http://www2.aueb.gr/users/ion/data/enron-spam/">Spam/Ham Email Dataset</a>

<h2>Implementasi</h2>
<h3>Algoritma J48</h3>
Algoritma J48 adalah sebuah algoritma turunan dari C4.5. Algoritma ini menghasilkan pohon biner dimana dalam proses klasifikasi pohon akan dibangun dan setiap tupel dari pohon tersebut akan diterapkan pada basis data dan hasil klasifikasi dari tupel tersebut. Algoritma J48 akan mengabaikan nilai yang tidak lengkap dalam proses pembuatan pohon. Dasar dari algoritma ini adalah untuk membagi data ke dalam beberapa bagian berdasarkan nilai atribut dari item yang ada pada training dataset. Algoritma J48 dapat melakukan klasifikasi baik melalui decision tree ataupun rules yang diperoleh dari pohon tersebut.<br>

<h3>Algoritma Naive Bayes</h3>
Naive Bayes adalah algoritma machine learning yang sering digunakan dalam masalah klasifikasi teks. Naive Bayes didasarkan pada teorema Bayes. Algoritma Naive Bayes disebut "naif" karena membuat asumsi bahwa kemunculan fitur tertentu tidak tergantung pada kemunculan fitur lainnya. Salah satu model dari Naïve Bayes yang sering digunakan dalam klasifikasi teks adalah multinomial Naive Bayes. Multinomial Naive Bayes merupakan metode supervised learning sehingga setiap data perlu diberikan label sebelum dilakukan training. Pada penelitian kali ini, kami menggunakan Naive Bayes Multinomial Text.<br>

<h2>Kesimpulan</h2>
Algoritma Naive Bayes lebih baik daripada J48 dalam kasus klasifikasi dan prediksi email spam. Naive bayes memiliki waktu yang lebih cepat dalam melakukan pemodelan dibandingkan J48. Terlihat pada gambar di atas hasil prediksi Naive Bayes lebih akurat daripada J48 dengan 20 email yang berhasil diklasifikasi dengan benar, sedangkan J48 hanya mengklasifikasi 17 email dengan benar.<br><br>

![image](https://user-images.githubusercontent.com/63483228/198871508-d4e2d226-2be8-43fe-b6b4-1c02b7b595d3.png)

![image](https://user-images.githubusercontent.com/63483228/198871510-989540b4-0888-4b09-a456-bebf0c57cae4.png)
