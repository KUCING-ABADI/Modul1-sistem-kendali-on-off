# Nama : Diki Agus
# NIM : 6702194021
# Nama : Dimas Salim
# NIM : 6702190047
# Nama Tim : Kucing Abadi

#           Modul 1 - Sistem-Kendali On - Off

• Dasar Teori Sistem Kendali On/Off
Dalam sistem kendali dua posisi, elemen pembangkit hanya mempunyai dua posisi
tertentu, yaitu “On” dan “Off” (Ogata, Katsuhiko, 1996: 199). Sehingga sistem
kendali dua posisi ini sering juga disebut dengan sistem kendali On/Off. Dalam sistem
kendali On/Off untuk memperoleh sinyal keluaran sistem dapat dilakukan dengan
mengambil dari sinyal keluaran pengendali yang cenderung tetap pada salah satu
nilai maksimum atau minimum, tergantung apakah sinyal pembangkit kesalahan
(error) positif atau negatif, sehingga Nilai kesalahan (error) pada sebuah robot line
follower adalah berupa data penyimpangan pembacaan sensor dari posisi/nilai
idealnya. Apabila nilai kesalahan telah terdeteksi, maka selanjutnya, dalam program
pengendalian robot LF diatur sedemikian rupa sehingga putaran aktuator robot (motor
DCMP) menjadikan robot bergerak dengan aksi yang tepat dalam rangka
mengembalikan posisi dan pergerakan robot LF menuju posisi yang diharapkan.
Sistem kendali ON-OFF berfungsi untuk menghasilkan sistem kontrol yang tetap dan
bersifat diskrit (discrete). Salah satu contoh sistem kendali on/off adalah pada
saat menyalakan dan mematikan sebuah motor listrik pada sebuah robot line follower.
Sistem kendali ini hanya memiliki dua perintah untuk motor listrik tersebut, yaitu
perintah start (1) dan stop (0) saja. Sedangkan pada sisi motor, hanya terdapat dua
buah feedback yaitu motor berputar dan motor berhenti berputar.

• Rincian Kegiatan Praktikum (Fungsi sensor pada rangkaian, cara kerja motor pada
rangkaian, dll)
- Fungsi sensor photo dioda pada rangkaian yaitu untuk mendeteksi gelap atau tidak lalu
mengirimkan sinyal gelap atau tidaknya pada arduino
- motor bekerja sebagai output dari sensor

• Kesimpulan Praktikum
Menjadi lebih mengerti tentang sistem kendali on - off.

• Referensi
https://www.robotics-university.com/2014/06/teori-teknik-pengendalian-onoff.html
