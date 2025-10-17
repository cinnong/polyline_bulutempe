# polyline_bulutempe
🏗️ Struktur dan Tipe Fitur
Berkas ini terdiri dari koleksi fitur (features) di mana setiap fitur merepresentasikan elemen jalan dengan tipe geometri LineString.

Tipe Geometri
Semua fitur jalan (kecuali jika ada relasi atau titik-titik tunggal yang diabaikan) menggunakan tipe geometri:
LineString: Digunakan untuk merepresentasikan jalan sebagai rangkaian dari dua atau lebih posisi berurutan.
Setiap posisi dalam coordinates merupakan array angka dalam urutan [longitude, latitude].

Identifikasi Jalan
Berikut adalah beberapa contoh fitur jalan yang teridentifikasi dalam berkas ini:

Jalan Utama (Trunk):
ID: way/180205942 
Nama: Jalan M.T. Haryono 
Tipe: trunk (jalan utama/nasional) 
Permukaan: asphalt 

Jalan Sekunder/Poros:
ID: way/247993773 
Nama: Jl. Poros Congko-Panyili 
Tipe: secondary 

Jalan Pemukiman (Residential):
ID: way/247015630 
Tipe: residential  (Umumnya adalah jalan di kawasan perumahan atau pemukiman)

Jalan Lingkungan (Living Street):
ID: way/247015638 
Tipe: living_street  (Area jalan di lingkungan perumahan di mana pejalan kaki memiliki prioritas)
