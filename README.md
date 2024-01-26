# Air_monitoring_System_Using Machine Learning
Sistem Klasifikasi Kualitas Udara menggunakan Algoritma  Random Forest berdasarkan Kadar CO dan CO2  menggunakan Sensor MQ7 dan MQ13 berbasis IoT. 

Dibuat oleh tim Mekatronika dan Kecerdasan Buatan 2021 UPI Purwakarta

- Aisyah Aira Putri Maharani - aisyahairaputrim@upi.edu
- Muhammad Ajis - muhazis02@upi.edu
- Sajidah Layali Robbaniyah - slayalir@upi.edu
- Muhamad Fajar Imanul Haq - muhamadfajarihaq@upi.edu
- Rizky Hamdani Sakti - rizkyhamm@upi.edu
- Muhammad Aviv Arrafi - avivarrafi28@upi.edu
- Abdu Malik Silaban - abdumalikh44@upi.edu

## Daftar Isi
1. Latar Belakang
2. Demo
3. Analisis Hasil
4. Referensi

## Latar Belakang
Udara merupakan salah satu unsur penting dalam kehidupan manusia selain air dan tanah. Unsur ini menjadi komponen utama penunjang keberlangsungan hidup manusia di dunia untuk melakukan berbagai aktivitas didalamnya. Udara mengandung berbagai zat seperti oksigen, karbon monoksida, karbon dioksida, dan sebagainya yang harus berada pada batas normal. Sayangnya, saat ini kualitas udara di Indonesia semakin memburuk.

Oleh karena itu, projek ini ditujukan untuk membentuk sebuah sistem pemantauan kualitas udara sebagai salah satu bentuk solusi penyelesaian yang dapat dilakukan saat ini. Sistem ini dipadukan dengan algoritma machine learning "random forest" untuk dapat mendeteksi kadar udara yang ditangkap oleh perangkat IoT secara real-time. 

## Demo
Komponen yang digunakan pada projek ini adalah:
- Sensor MQ-7
- Sensor MQ-135
- Arduino Mega
- ESP 8266
- Project Board
- Kabel Jumper

Berikut adalah skematik sistem:

![WhatsApp Image 2024-01-26 at 14 48 13_c63ca5d3](https://github.com/aisyaaaptr/Air_monitoring_System_Machine-Learning/assets/157786477/8c95296f-cd15-417c-8335-ba3b6edc103c)

Video demo alat dapat dilihat disini: https://youtu.be/obFfvud55Ws?si=M5qHvbJPSkecOkDV 

## Analisis Hasil
Perancangan sistem deteksi kualitas udara ini dilakukan dengan memanfaatkan 2 jenis sensor gas yaitu MQ-7 dan MQ-135 yang berbasis mikrokontroler ESP8266 dan Arduino Mega. Sistem ini juga menggunakan Algoritma machine learning Random Forest untuk mengklasifikasi kadar gas CO dan CO2 dalam ppm yang terdeteksi oleh sistem. Hasil klasifikasi akan dibedakan menjadi 3 kelas, yaitu “baik”, “buruk”, dan “toxic”. 

Dalam proses pelaksanaan pengujian klasifikasi Algoritma machine learning Random Forest, ditemukan 1 data yang tidak sesuai dari total keseluruhan 100 kali percobaan yang telah dilakukan. Oleh karenanya, Algoritma machine learning Random Forest dapat digunakan dengan baik dalam mendeteksi kadar udara di lingkungan sekitar karena berhasil memberikan nilai akurasi sebesar 99%.

## Referensi
- [1] H. Risa Aisyiah, Alat Pendeteksi Kualitas Udara. 2019.
- [2] J. M. S. Waworundeng and O. Lengkong, “Sistem Monitoring dan Notifikasi Kualitas Udara dalam Ruangan dengan Platform IoT,” CogITo Smart J., vol. 4, no. 1, pp. 94–103, 2018, doi: 10.31154/cogito.v4i1.105.94-103.
- [3] B. Sidabutar, E. Kurniati, and K. Adelia, “Evaluasi Kualitas Udara Emisi Gas Buang/Ambien di PLTD Kahayan Baru,” J. Phys. It’s Appl., vol. 3, no. 1, pp. 226–230, 2023.
- [4] A. A. Rosa, B. A. Simon, and K. S. Lieanto, “Sistem Pendeteksi Pencemaran Udara Portabel Menggunakan Sensor MQ-7 dan MQ-135,” Ultim. Comput. J. Sist. Komput., vol. 12, no. 1, pp. 23–28, 2020, doi: 10.31937/sk.v12i1.1611.
- [5] L. Agustinus, F. A. Setyangsih, and T. Rismawan, “Rancang Bangun Prototype Pendeteksi Kadar CO Sebagai Informasi Kualitas Udara Berbasis Mikrokontroler,” J. Coding Sist. Komput. Untan, vol. 03, no. 2, pp. 44–53, 2015.
- [6] A. S. Mannaf, F. A. Setyaningsih, and I. Ruslianto, “Purwarupa Sistem Deteksi Dan Pengurangan Kadar Co, Co2 Dan No2 Berbasis Mikrokontroler,” J. Coding, Sist. Komput. UNTAN, vol. 04, no. 3, pp. 1–8, 2016, [Online]. Available: https://jurnal.untan.ac.id/index.php/jcskommipa/article/view/16469%0Ahttps://jurnal.untan.ac.id/index.php/jcskommipa/article/download/16469/14273
- [7] F. Rivaldi, R. Maulana, and M. H. H. Ichsan, “Sistem Deteksi Pencemaran Gas Beracun CO, HC, NOx dalam Ruangan Tertutup dengan Metode Support Vector Machine,” J. Pengemb. Teknol. Inf. dan Ilmu Komput., vol. 6, no. 8, pp. 4033–4038, 2022, [Online]. Available: http://j-ptiik.ub.ac.id
- [8] R. Kumar, S. Singla, and J. Bansal, “IOT Based Air Pollution Monitoring Sy
