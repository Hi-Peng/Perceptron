# Perceptron in Python

#### Pendahuluan
>Dalam *repository* ini, kita akan mempelajari Perceptron dan  menuliskan programnya dalam bahasa Python. Kami sangat menyarankan pengetahuan akan aljabar linier dan kalkulus yang cukup (menengah, yo sitik sitik iso turneh mudeng). Selain prasyarat pada kemampuan matematis, diharapkan juga kemampuan pemahamaan operasi vektor dan matriks pada python juga disarankan.

Perceptron merupakan salah satu jenis algoritma yang digunakan untuk *machine learning*. Algoritma ini digunakan untuk mengklasifikasi secara biner. Perceptron juga dapat disebut sebagai *single layer neural network*. 
Perceptron terdiri atas 4 bagian penting yaitu *input values* (nilai), *weights/bias*, dan *sum value* serta *activation function*. Cara kerja dari algoritma ini adalah mengkalikan *input values* dengan *weights + bias*, kemudian menjumlahkan nilai tersebut yang nantinya nilai itu akan dimasukan pada *activation function*. 
![Perceptron](perceptron.jpg)
Pada bagan tersebut dijelaskan bahwa input (dalam neural network disebut dengan input neuron) berisi variable $x$ dan *constant* bernilai 1. *Contant* inilah yang disebut dengan *bias*. Seluruh nilai input dan bias dikalikan dengan *weights*. Hasil perkalian masing-masing inputan dengan weights dijumlahkan pada neuron penjumlah (Weighted Sum). Fungsi penjumlahan secara matematis dituliskan pada persamaan berikut.
$$\sum\limits_{i=0}^nw_nx_n$$
Hasil penjumlahan kemudian dimasukan pada *activation function* (fungsi aktivasi) yang berupa fungsi *step*, fungsi sigmoid, maupun fungsi ReLU.
Dari penjelasan tersebut, dapat dirumuskan algoritma dari Perceptron.
```{r, eval=FALSE}
Inisialisasi variabel x, w, w_sum, b

    loop through each measurement of the current species
    ...
etc.
```

#### Aplikasi
Sebagai contoh, perceptron akan digunakan untuk menentukan hasil operasi gerbang logika AND dan OR. 


