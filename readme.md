# sistem-embeded2223
Project tugas kuliah Sistem Embeded 22/23

Progam Studi D4 Teknik Telekomunikasi Politeknik Negeri Semarang

Anggota Kelompok

Azarya Paska Saputra 4.31.20.0.05

Laurensius Liquori Igridfian 4.31.20.0.13

Pangestu Aji Tri Laksono 4.31.20.0.19


**ESP32** adalah nama dari mikrokontroler yang dirancang oleh perusahaan yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol komunikasi seperti I2C, UART dan SPI.

ALAT DAN BAHAN
-------------------------------
ESP32
Breadboard
Kabel jumper
Potensiometer 10k Ohm (1)
Sensor Capacitive Soil Moisture
LED (5) dan Push Button (3)
Multimeter
Resistor 330,1K, 10K Ohm (@ 3)
HASIL KELUARAN

1. Instal lebih dulu Board ESP32 pada Arduino IDE
Klik menu Tools > Board: > Pilih Boards Manager lalu Pada kolom pencarian tulis ESP32 kemudian install dan tunggu sampai selesai.
2) Mengakses GPIO ESP32
a) Program ini bisa mengendalikan satu LED dengan push button dimana LED bisa menyala apabila push button ditekan dan akan mati apabila dilepaskan.
b) Selanjtunya pada program GPIO yang kedua, ditambahkan 1 LED yang akan mati selama 5 setik dan menyala selama 5 detik. Apabila push button tetap ditekan tetapi waktu sudah habis, LED akan tetap mati.
c) Pada percobaan GPIO yang ketiga menggunakan 3 LED yang dikendalikan oleh satu push button. Saat push button ditekan maka LED akan menyala secara berurutan (continue).

2. Mengakses PWM ESP32
a) Percobaan ini menggunakan metode Pulse Width Modulation yaitu pendekatan pelebaran pulsa yang menghasilkan nilai tegangan analog dengan maksimal tegangan HIGH 3,3 V dan LOW 0 V. Pin pada PWM mengeluarkan sinyal digital yang dihasilkan dari dutty cycle (perbandingan HIGH dan LOW dalam 1 periode). LED akan menyala 5x lebih terang. Karena terdapat delay 0,015 maka LED akan redup dengan kecepatan 0,015 detik, lalu kemudian akan terang kembali.
b) Percobaan yang kedua hampir sama dengan PWM yang pertama, hanya saja menggunakan 3 LED.

3. Mengakses ADC and DAC ESP32
a) Percobaan ini menggunakan potensiometer yang menghasilkan output apabila potensiometer diputar. Semakin ke kanan maka nilainya akan semakin bertambah dan sebaliknya.
b) Percobaan ini ditambahkan dengan LED dan GPIO. Ketika program ini dijalankan akan menghasilkan output apabila potensiometer diputar ke kanan maka lampu akan semakin terang nyala lampunya dan begitupun sebaliknya.
