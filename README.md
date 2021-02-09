# Intent

Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar
komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum
intent dalam aplikasi Android yaitu :
- [x] Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- [x] Menjalankan background service, misalnya melakukan sinkronisasi ke server dan
menjalankan proses berulang (periodic/scheduler task).
- [x] Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi
membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai
melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh
sistem Android untuk event booting tersebut.

## Intent dibagi menjadi 2 yaitu 
- [x] Intent Explicit yang berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
- [x] Intent Implisit yang berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti : Dial Number, dan lainnya.

![Intent](https://user-images.githubusercontent.com/63852448/107376938-078f7d80-6b1d-11eb-9390-d0cf080f63ab.jpeg)

![Intentt2](https://user-images.githubusercontent.com/63852448/107376961-0cecc800-6b1d-11eb-959e-c17515f0dea9.jpeg)
