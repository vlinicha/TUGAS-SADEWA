# MENYALAKAN LAMPU LED MENGGUNAKAN HP KONEKSI WIFI LOKAL

# ALAT DAN BAHAN:
1. ESP32
2. komputer + Arduino IDE
3. Kabel micro usb
4. Project board
5. Kabel jumper wires female to male
6. LED
7. Resistor 220-330 ohm

# LANGKAH KERJA :
1. Pertama-tama anda harus menginstal software Arduino IDE di komputer anda
2. Setelah menginstal software Arduino IDE, anda juga harus menginstal library ESP32 (https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json)
3. Masukkan program yang sudah tertera di atas pada Arduino IDE (cara penginstalan ada pada file di atas)
4. Sambungkan ESP32 dengan komputer menggunakan kabel micro usb
5. Upload program  ke dalam esp32 yang sudah dimasukkan di Arduino IDE tadi
6. Jika sudah terupload maka tunggu beberapa saat hingga layar bagian bawah sofeware Arduino IDE menunjukkan angka 100% (contoh ada pada gmbar ada di file atas)
7. Setelah itu sambungkan hp kalian dengan jaringan wifi yang sudah di program tadi, masukkan password sama dengan yang ada di program tadi
8. Jika sudah terkoneksi, kalian bisa membuka serial monitor yang ada di Arduino IDE dan dapat mengetahui alamat IP dari jaringan wifinya
9. Lalu kalian buka web pada hp kalin dan masukan alamat IP tadi hingga muncul laman berisi tulisan on berwarna hijau (seperti contoh di file atas)
10. Dan web itulah yang membantu kalian untuk mengoprasikan lampu LED agar bisa hidup dan mati sesuai keinginan kalian, selamat mencoba:)

# SKEMA WIRING/PENGKABELAN:
1. Pertama tata LED pada project board dengan rapi
2. Hubungkan salah satu kaki resistor dengan kaki katoda LED dan satu kaki lainnya ditancapkan di jalur negatif project borad, lakukan hal yang sama LED lainnya
3. Lalu kaki anoda LED di hubungkan dengan pin dari ESP32 (contoh pin yg digunakan 25,26,27,32,33)
4. Dan terakhir hubungkan semua kaki resistor yang berada di jalur negatif dengan ground ESP32 menggunakan kabel jumper
5. Untuk lebih jelaskan lihat gambar yang tertera di file atas





