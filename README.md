# Klasifikasi Daun Pepaya dan Daun Jeruk Nipis

## Deskripsi singkat
Pengumpulan sampel data yang digunakan dalam penelitian ini berupa daun jeruk nipis dan daun pepaya sejumlah 100 daun yang terdiri 50 daun dari masing – masing jenis. 

1. Daun Pepaya : 50 Image
2. Daun Jeruk Nipis : 50 Image

Dataset dapat diliat pada link berikut https://github.com/TivanoGhunawn/DatasetAI.git

Lalu Teknik Deep Learning yang digunakan adalah Model dengan menggunakan algoritma CNN (Convolutional Neural Network)
Sebelum masuk ke metode CNN terdapat tiga tahapan utama, yang terdiri atas input, proses, dan output.

 1) Input: Pada bagian input terdapat 2 jenis daun yaitu daun pepaya dan daun jeruk nipis yang akan diidentifikasi. Agar dapat memprediksi jeruk nipis atau pepaya, data input model harus mengikuti format sebagai berikut:
•	Gambar dengan format umum seperti .jpeg, .png, .webp, dsb.
•	Gambar dikonversi ke dalam bentuk array/tensor
•	Nilai pixel gambar memiliki rentang nilai 0-1 dengan cara membagi semua nilai pixelnya dengan 255.0

 2) Proses: Data gambar yang telah diambil akan di pre-processing terlebih dahulu sebelum masuk pada CNN. Tujuan dari pre-processing ini adalah untuk menghilangkan noise, memperjelas fitur data gambar, memperkecil ukuran gambar, dan mengubah data gambar daun agar dapat diproses oleh CNN. Selanjutnya, data gambar diproses melalui convolutional layer, pooling layer, flatten, dan fully connected layer. 

3) Output: Pada bagian output akan menampilkan hasil klasifikasi berupa prediksi gambar daun herbal, sehingga pengguna lebih mudah dalam mengetahui jenis daun herbal.

Daun memiliki banyak fitur, seperti bentuk, tekstur dan pola. Maka dari itu paper ini fokus pada pengenalan daun melalui warna, tekstur, ukuran, dan bentuknya menggunakan metode CNN. Convolutional Neural Network merupakan salah satu jenis algoritme Deep Learning yang dapat menerima input berupa gambar, menentukan aspek atau obyek apa saja dalam sebuah gambar yang bisa digunakan mesin untuk “belajar” mengenali gambar, dan membedakan antara satu gambar dengan yang lainnya.Data yang sudah dikumpulkan akan diklasifikasi menggunakan metode CNN dan menghasilkan akurasi seperti tabel dibawah ini.

# Author
Tivano Ghunawan 201910370311080
