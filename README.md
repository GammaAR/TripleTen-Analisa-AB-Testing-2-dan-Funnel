# TripleTen Analisa AB Testing 2 dan Funnel

Pada situasi kali ini, kita bekerja di sebuah startup yang menjual produk makanan. Kita perlu mencari tahu perilaku pengguna aplikasi dari perusahaan tersebut. Pertama akan dicari jalur Funnel yang dilalui oleh pengguna untuk memesan suatu makanan, bagaimana tahapannya, dan berapa banyak pengguna yang berhenti di suatu tahap? Kemudian akan dilihat hasil dari A/A/B testing, Tim web designer ingin mengubah font untuk keseluruhan aplikasi, tetapi product manager merasa khawatir jika para pengguna justru akan merasa bahwa desain baru tersebut mengganggu. Mereka pun memutuskan untuk mengambil keputusan berdasarkan hasil A/A/B testing. Para pengguna dibagi menjadi tiga kelompok: dua kelompok kontrol diperlihatkan dengan versi font lama dan satu kelompok uji diperlihatkan dengan versi font terbaru. Tugas kita adalah mencari tahu font mana yang akan memberi hasil terbaik.

/datasets/logs_exp_us.csv

-  EventName — nama peristiwa
-  DeviceIDHash — ID unik pengguna
-  EventTimestamp — waktu peristiwa
-  ExpId — nomor eksperimen: 246 dan 247 untuk kelompok kontrol, 248 untuk kelompok uji
