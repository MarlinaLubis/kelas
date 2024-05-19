# Hyperparameter

![Alt text](image.png)

Teori Menjelaskan :
* Definisi Hyperparameter : adalah parameter yang ditetapkan sebelum proses pelatihan model dimulai dan tidak diperbarui selama pelatihan.
* Iterasi : berapa kali menjalankan satu epoch
* Epoch : satu putaran lengkap untuk melalui seluruh set data latih dari batch size
* Batch Size : jumlah sampel data yang masuk dalam satu dikali pelatihan

## Pengembangan Dataset

Kembangkan dataset dengan topik masing masing yang dipilih sebanyak 400+400 pasang.

## Optimasi Hyperparameter

Tentukan nilai nilai dan hitung akurasi dari setiap hyperparameter yang diubah
* Batch size = 10, epoch = 300 : di testing dengan data yang valid = 6, tidak valid = 4 dihasilkan akurasi 60%.
* Batch size = 20, epoch = 200 : ditesting dengan data yang valid = 7, tidak valid = 3 dihasilkan akurasi 70%.
* Batch size = 30, epoch = 200 : ditesting dengan data yang valid = 7, tidak valid = 3 dihasilkan akurasi 70%

## Kerjakan

1. Pilih topik dataset yang akan dikembangkan, tidak boleh sama dengan yang lain
2. Topik kordinasi dengan ketua kelas dan kelas lainnya jangan sampai sama
3. Jalankan file training.py berdasarkan hyperparameter yang ditentukan
4. Output dari training menghasilkan satu buah model, buatlah kode program python untuk me load model tersebut kemudian meminta inputan dari user dan outputan dari hasil model
5. Ukur akurasi dari setiap inputan dan outputan model tersebut per hyperparameter kemudian di rekap dalam spreadsheet
6. Jelaskan setiap error yang didapatkan ketika menjalankan program, berikut solusi untuk mengatasinya
