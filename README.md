# Machine-Learning-Linier-Regression

Pada latihan ini, tugas kita adalah mengimplementasikan regresi linier dengan satu variabel untuk memprediksi keuntungan untuk sebuah truk makanan. Misalkan Anda adalah CEO dari sebuah waralaba restoran dan sedang mempertimbangkan kota-kota yang berbeda untuk membuka outlet baru. Tujuan kita adalah untuk membuat model regresi linier yang dapat memprediksi keuntungan truk makanan berdasarkan jumlah penduduk di kota tersebut. Kita akan menggunakan gradient descent untuk mencari nilai koefisien dari model regresi linier yang sesuai.

Dari hasil praktikum diatas diketahui bahwa hasil prediksi memiliki nilai keakuratan yang baik hal itu dibuktikan dengan hasil erornya yang kecil juga semakin tinggi epochnya semakin kecil erornya, Maka dari itu dimungkinkan untuk menggunakan Regresi Linier dengan algoritma gradient desenct untuk melakukan prediksi mengenai profit dari penjualan food truck.

Untuk melakukan prediksi profit dari penjualan food truck dengan Regresi linier maka hal langkah-langkahnya sebagai berikut:
1. import library numpy, pandas dan matplotlib
2. import datanya dan load datanya
3. kalsifikasikan datanya menggunakan data.describe(), Hal ini bertujuan agar mempermudah dalam melakukan pengolahan data juga mengetahui distribusi dari data.
4. ploting datanya
5. hitunglah costnya semakin kecil nilai cosnya maka semakin bagus model regresi liniernya dan sebaliknya.
6. Tambahkan satu kolom agar kita dapat menggunakan solusi vektorisasi untuk menghitung biaya dan gradient.
7. Spliting data juga definisikan varibel training juga target, data input (X) diisikan dengan semua kolom pada DataFrame kecuali kolom terakhir, sedangkan data output (y) diisikan dengan kolom terakhir pada DataFrame.
8. Convert nilai X dan Y ke matriks juga definiskan varibael theta.
9. hitung initial  cost 
10. Lakukan proses pelatihan atau training pada model linear regression menggunakan algoritma gradient descent.
11. Inisialisasi beberapa variabel tambahan - learning rate alpha, dan jumlah iterasi yang akan dilakukan.
12. Jalankan algoritma gradient descent untuk menyesuaikan parameter theta dengan set latihan.
13. computeCost(X, y, g) hasilnya kita akan tau biaya (cost) dari model yang dilatih menggunakan parameter yang kami pasang.
14. Plot model linier beserta datanya untuk melihat secara visual seberapa cocok model tersebut.
15. Plot juga Error vs. Training Epoch.
