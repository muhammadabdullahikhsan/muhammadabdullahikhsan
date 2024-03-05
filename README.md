Simple Search And Binar Search
-chapter 01:introduction to Algoritms
Algoritma didefinisikan untuk sekumpulan instruksi untuk menyelesaikan tugas tertentu  
Binary Search suatu algoritma pencarian yang digunakan pada list yang terurut. Inputnya berupa list yang terdiri dari elemen-elemen terurut secara alfabetik atau angka. Algoritma ini akan mencari elemen tertentu dalam list. Jika ditemukan, akan mengembalikan posisinya. Jika tidak, akan mengembalikan nilai kosong.
- Binary search hanya bisa digunakan jika data sudah diurutkan terlebih dahulu, misal daftar nama dalam kamus.
- Gunakan list untuk menyimpan kumpulan data
- Struktur data lain seperti string dan tuple juga dapat digunakan.
Simple search atau sequential search melakukan pencarian secara berurutan dari awal. Butuh banyak waktu. Binary search lebih efisien karena setiap tebakan langsung menyempitkan rentang menjadi setengah.
Perbandingan Simple Search dan Binary Search Simple search atau sequential search melakukan pencarian secara berurutan dari awal. Butuh banyak waktu. Binary search lebih efisien karena setiap tebakan langsung menyempitkan rentang menjadi setengah.

Running Time & Big o Notation
-dua pendekatan utama dalam algoritma dibahas, yaitu pencarian sederhana (simple search) dan pencarian biner (binary search). Pencarian sederhana dilakukan dengan mengecek setiap elemen satu per satu, sedangkan pencarian biner membagi data menjadi dua bagian dan mencari di salah satu bagian berdasarkan aturan tertentu.
-Penggunaan notasi Big O menjadi fokus utama dalam analisis kinerja algoritma. Notasi ini digunakan untuk mengukur kompleksitas waktu algoritma, yaitu seberapa cepat algoritma tersebut berjalan seiring dengan pertumbuhan ukuran masukan.
-Binary search dianggap lebih efisien daripada pencarian sederhana karena memiliki kompleksitas waktu yang lebih rendah, terutama untuk ukuran masukan yang besar. Ini karena binary search memiliki pertumbuhan logaritmik, sedangkan pencarian sederhana memiliki pertumbuhan linear.
-Penting untuk memahami berbagai notasi dalam analisis kinerja algoritma, seperti O(n) (linear time), O(log n) (logarithmic time), O(n^2) (quadratic time), dan O(n!) (factorial time). Setiap notasi ini menggambarkan tingkat pertumbuhan waktu algoritma seiring dengan pertumbuhan ukuran masukan.
-Penekanan bahwa kecepatan algoritma diukur berdasarkan pertumbuhan jumlah operasi, bukan waktu sebenarnya, adalah aspek penting dalam analisis kinerjaalgoritma. Ini membantu memahami bahwa algoritma yang memiliki jumlah operasi lebih sedikit akan lebih efisien, terlepas dari perbedaan dalam waktu eksekusi yang mungkin terjadi.
