# Spam Detection Using Weka

<h2>Rumusan Masalah</h2>
Setiap hari pengguna email menerima ratusan pesan spam dengan konten baru, dari alamat baru yang secara otomatis dihasilkan oleh perangkat lunak robot. Untuk menyaring spam dengan metode tradisional seperti daftar hitam-putih (domain, alamat IP, alamat surat) hampir tidak mungkin. Penerapan metode text mining pada E-mail dapat meningkatkan efisiensi penyaringan spam. Juga mengklasifikasikan pesan spam akan memungkinkan untuk membangun ketergantungan tematik dari geografis.

<h2>Tujuan Penelitian</h2>
Untuk memeriksa bahwa email tersebut adalah spam atau bukan melalui klasifikasi teks di WEKA.

<h2>Dataset</h2>

<b>Source: </b><a href="http://www2.aueb.gr/users/ion/data/enron-spam/">Spam Email Datasets</a>

<h2>Implementasi</h2>
<h3>Algoritma J48</h3>
Algoritma J48 adalah sebuah algoritma turunan dari C4.5. Algoritma ini menghasilkan pohon biner dimana dalam proses klasifikasi pohon akan dibangun dan setiap tupel dari pohon tersebut akan diterapkan pada basis data dan hasil klasifikasi dari tupel tersebut. Algoritma J48 akan mengabaikan nilai yang tidak lengkap dalam proses pembuatan pohon. Dasar dari algoritma ini adalah untuk membagi data ke dalam beberapa bagian berdasarkan nilai atribut dari item yang ada pada training dataset. Algoritma J48 dapat melakukan klasifikasi baik melalui decision tree ataupun rules yang diperoleh dari pohon tersebut.<br>

<h3>Algoritma Naive Bayes</h3>
Naive Bayes adalah algoritma machine learning untuk masalah klasifikasi. Ini didasarkan pada teorema probabilitas Bayes. Hal ini digunakan untuk klasifikasi teks yang melibatkan set data pelatihan dimensi tinggi. Beberapa contohnya adalah penyaringan spam, analisis sentimen, dan klasifikasi artikel berita. Algoritma Naive Bayes adalah algoritma yang mempelajari probabilitas suatu objek dengan ciri-ciri tertentu yang termasuk dalam kelompok/kelas tertentu. Dengan kata lain, adalah pengklasifikasi probabilistik.

<h3>Referensi</h3>
-> https://github.com/waleedaliSe/Spam-Detection-Using-Weka <br>
-> https://www.academia.edu/38524197/Comparison_of_four_email_classification_algorithms_using_WEKA
