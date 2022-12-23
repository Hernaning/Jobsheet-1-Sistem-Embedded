# Jobsheet-1-Sistem-Embedded


Teori Singkat


ESP-32 adalah mikrokontroler yang dikenalkan oleh Espressif System merupakan penerus dari mikrokontroler ESP8266. Pada mikrokontroler ini sudah tersedia modul WiFi dalam chip sehingga sangat mendukung untuk membuat sistem aplikasi Internet of Things. Perbedaan antara ESP32 dengan ESP8266 adalah pada bagian prosesornya. ESP32 sudah Dual-Core 32 bit, jelas lebih cepat ESP32 secara kinerja. Selain itu modul ini juga mempunyai bluetooth, satu fitur yang tidak ada di ESP8266.



a) GPIO

Buatlah rangkaian seperti pada Gambar di bawah ini


![Rangkaian GPIO 1](https://user-images.githubusercontent.com/119298912/208895086-ba9ca70c-7b6f-43c1-aaf3-8ec41033179b.jpg)


Buatlah program seperti pada script di bawah ini untuk mengendalikan led menggunakan push button. Kemudian upload program tersebut pada ESP32 dan berikut adalah hasilnya




https://user-images.githubusercontent.com/119298912/209267429-fa09839f-51ab-40f9-ae1c-9e319110cd32.mp4




Tambahkan 1 LED dan 1 push button pada rangkaian



![Rangkaian GPIO 2 3 (2)](https://user-images.githubusercontent.com/119298912/209339895-6b1d3d49-7d6c-4d22-8f5f-a0b5059992bd.jpg)



Kemudian kembangkan program agar ketika push button ke-2 ditekan, LED akan melakukan blink setiap 500 ms sekali. Berikut hasilnya



https://user-images.githubusercontent.com/119298912/209341286-0c428f43-a5cf-4883-84ee-9d0600c6ca72.mp4



Tambahkan 3 LED dan 1 push button pada rangkaian, kemudian kembangkan program agar ketuka push button ke-3 ditekan, LED akan menyala menjadi running led (menyala bergantian dari kiri ke kanan). Berikut hasilnya




https://user-images.githubusercontent.com/119298912/209342280-78ef0218-3aec-4564-a5cc-f92de55d8855.mp4





b) PWM


Buatlah rangkaian seperti pada gambar di bawah ini.



![pwm](https://user-images.githubusercontent.com/119298912/209266903-932d872e-edd3-470a-9dee-26cd42144430.jpg)



Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta berikut adalah dokumentasikan hasilnya.



https://user-images.githubusercontent.com/119298912/209341028-b4db4174-4106-45f8-9f4a-bfe10a870d7b.mp4


Buatlah program lanjutan seperti pada script berikut ini. Upload program tersebut, kemudian amati dan analisis apa yang terjadi serta 
dokumentasikan hasilnya.



https://user-images.githubusercontent.com/119298912/209342606-1d75d868-0070-4716-94f9-942094829a54.mp4



c) ADC dan DAC

Buatlah rangkaian seperti pada gambar di bawah ini.



![adc dan dac](https://user-images.githubusercontent.com/119298912/209343093-19ac3932-72b5-4d21-ba8b-faa498015521.jpg)


Putar potensiometer secara perlahan agar mendapatkan nilai 0 hingga 4095 pada tampilan serial monitor. Analisis apa yang terjadi dan dokumentasikan hasilnya.


https://user-images.githubusercontent.com/119298912/209343450-a110afcc-9818-4f36-937b-7a120df7ae53.mp4


Buatlah program seperti pada script berikut ini.Tambahkan LED pada GPIO


https://user-images.githubusercontent.com/119298912/209343792-f3e0af54-86ce-4152-a4c8-24614752190f.mp4


