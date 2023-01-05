# Embedded-System-Jobsheet-2
Ayudya Sawitri

TE-3B/4.31.20.1.05

PROTOKOL KOMUNIKASI DAN SENSOR

A. ESP32 Capacitive Touch Sensor

Buka Arduino IDE dan upload script program berikut ke ESP32.

Buka serial monitor untuk melihat raw data. Ubah tampilan serial monitor menjadi Serial Plotter pada menu Tools > Serial Plotter.

Sentuh ujung kabel jumper dan amati yang terjadi, kemudian dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121160856/209056093-89f86f79-9589-47ad-99b6-e30e3c3603df.MOV



Buatlah program agar LED menyala ketika sensor disentuh, dan LED akan mati ketika sensor tidak disentuh.



Buatlah program agar ketika sensor disentuh, LED menyala Blink.



https://user-images.githubusercontent.com/121160856/209055545-2f70353a-13e7-4334-9425-e2fa1bed23ce.MOV



Buatlah program agar ketika LED menyala, maka pada Serial Monitor akan menampilkan angka yang akan bertambah setiap kali sensor disentuh.



https://user-images.githubusercontent.com/121160856/209055337-b223ae0d-fe70-41af-b701-686284e34f8f.mp4



Tambahkan 2 LED sehingga pada rangkaian terdapat 3 LED. Buatlah program agar ketika sensor disentuh, LED menyala menjadi running LED.
Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian kanan ke kiri secara kontinyu



https://user-images.githubusercontent.com/121160856/209054827-7e7925d1-a0fe-43f4-9e5f-ce5300468b06.MOV



B. Mengakses Sensor DHT 11 (Single Wire / BUS)

Buatlah program agar ketika suhu rungan mencapai 30 derajat celcius, maka ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila
suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan LED berbentuk running LED seperti pada Percobaan A. Kemudian dokumentasikan hasilnya.



https://user-images.githubusercontent.com/121160856/209052764-688211fd-d198-41f4-9070-8e0575cdbe7e.mp4



C. Mengakses Sensor RFID (SPI Communication)

Buatlah program seperti pada script berikut ini.
Dekatkan kartu atau Tag RFID ke RFID Reader. Amati dan analisis cara kerja programnya.



https://user-images.githubusercontent.com/121160856/209054440-6f149b6c-4601-43d3-9cfc-9450958705d0.mp4



Buatlah program agar Tag RFID yang terbaca sebelumya dapat digunakan untuk hak akses. Apabila Tag RFID didekatkan pada Reader, maka LED
Hijau akan menyala, servo akan bergerak ke kanan (lalu kembali ke posisi semula setelah 3 detik) dan di Serial Monitor akan tertampil pesan “Akses
Diterima, Silahkan Masuk”. Apabila Tag RFID tidak dikenali, maka LED Merah akan menyala, servo tidak bergerak dan di Serial Monitor akan tertampil pesan “Akses Ditolak”. Gunakan Tag RFID lain untuk mencoba.



https://user-images.githubusercontent.com/121160856/209053779-10977843-d1a9-403b-9060-df6935f935f1.mp4

