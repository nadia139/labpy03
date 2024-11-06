1. Tujuan Program:
Menghasilkan sejumlah N bilangan acak yang nilainya lebih kecil dari 0.5

Alur Program:
Inisialisasi
Import fungsi random dari modul random
Buat fungsi generate_numbers yang menerima parameter n (jumlah bilangan yang diinginkan)
Inisialisasi counter (count = 1)
Input
Program meminta input dari user berupa nilai N
Input divalidasi harus berupa angka integer
Proses Utama
Loop WHILE akan berjalan selama count <= N
Dalam setiap iterasi: a. Generate bilangan random antara 0-1 menggunakan random() b. Cek apakah bilangan < 0.5 c. Jika ya:
Tampilkan bilangan
Increment counter d. Jika tidak:
Skip dan generate bilangan baru
Loop berlanjut sampai mendapatkan N bilangan yang memenuhi syarat
Output

Menampilkan setiap bilangan yang memenuhi syarat dengan format: "data ke: [urutan] => [bilangan random]"
Menampilkan "Selesai" ketika program berakhir

https://drive.google.com/file/d/1dr3DAp9VsTFPrI2xl7eqE0nLt5CSgN8j/view?usp=drivesdk


