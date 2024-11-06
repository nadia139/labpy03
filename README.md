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

<img width="960" alt="latihan 1" src="https://github.com/user-attachments/assets/39b81796-b59e-4a13-a579-9b30b0fd045a">



2. Tujuan Program:
Menghitung total keuntungan usaha selama 8 bulan dengan persentase laba yang berbeda-beda

Alur Program:
Inisialisasi

Set modal awal = 100 juta
Inisialisasi total_laba = 0
Buat list kosong untuk menyimpan laba per bulan
Proses Perhitungan

Loop FOR untuk 8 bulan (range 1-9)
Untuk setiap bulan, hitung laba berdasarkan kondisi: a. Bulan 1-2: Laba = 0 (belum dapat untung) b. Bulan 3-4: Laba = 1% dari modal (modal * 0.01) c. Bulan 5-7: Laba = 5% dari modal (modal * 0.05) d. Bulan 8: Laba = 3% dari modal (modal * 0.03)
Setiap laba bulanan: a. Ditambahkan ke total_laba b. Disimpan ke dalam list laba_per_bulan c. Ditampilkan ke layar
Output

Menampilkan laba setiap bulan
Menampilkan total laba keseluruhan

<img width="960" alt="latihan 2" src="https://github.com/user-attachments/assets/c9639625-0c44-4ba9-b818-3602cbf8e702">



3. Tujuan Program:
Mensimulasikan mesin ATM sederhana dengan fitur cek saldo dan penarikan uang

Alur Program:
Inisialisasi

Set saldo awal = Rp 1.000.000
Program berjalan dalam infinite loop (while True)
Menu Utama

Tampilkan saldo saat ini
Tampilkan menu pilihan:
Tarik Uang
Keluar
Minta input pilihan dari user
Proses Berdasarkan Pilihan

Jika pilihan = 1 (Tarik Uang): a. Minta input jumlah penarikan b. Validasi input:

Harus berupa angka (try-except untuk ValueError)
Jumlah penarikan harus <= saldo
Jumlah penarikan harus > 0 c. Jika valid:
Kurangi saldo dengan jumlah penarikan
Tampilkan pesan sukses d. Jika tidak valid:
Tampilkan pesan error yang sesuai
Jika pilihan = 2 (Keluar): a. Tampilkan pesan terima kasih b. Break dari loop (program selesai)

Jika pilihan tidak valid: a. Tampilkan pesan error b. Kembali ke menu utama

Fitur Keamanan

Validasi input harus berupa angka
Validasi saldo mencukupi
Validasi jumlah penarikan positif
Error handling untuk input tidak valid
Output

Menampilkan saldo terkini setiap kali menu ditampilkan
Menampilkan pesan sukses/error sesuai dengan aksi yang dilakukan
Menampilkan pesan terima kasih saat keluar

<img width="960" alt="latihan 3" src="https://github.com/user-attachments/assets/0863ac97-e15d-42d5-be48-4c514f7efefd">







