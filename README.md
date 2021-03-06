# Plugin ButterKnife dan Parcelable

 ButterKnife adalah library Android yang dikembangkan oleh Jake Wharton. Library ini sangat membantu meringankan tugas developer android karena mampu menyederhanakan penulisan komponen view di Android, atau istilah singkatnya kita bisa menghilangkan ‘findViewById’.
 
 Parcelable adalah suatu interface pada pemrograman Android, yang memungkinkan suatu instansi dari kelas/objek untuk bisa disimpan dan diambil kembali dari sebuah Parcel. Sedangkan Parcel sendiri merupakan suatu kontainer untuk menampung kelas tersebut.

# Intent Result

Intent merupakan suatu objek yang terdapat dalam suatu activity dimana objek tersebut dapat komunikasi dengan activity yang lain, baik activity pada fungsi internal android misal seperti memanggil activity dalam satu package atau beda package yang masih berada dalam satu project.

Ada tiga penggunaan umum intent :

1. Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
2. Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
3. Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.

Pada Intent Result ini dapat mengirim data ke activity lainnya (pindah halaman dengan membawa data) . Ada 2 cara untuk mengirimkan data/nilai antar activity didalam aplikasi Android, yaitu dengan menggunakan Intent dan Bundle, keduanya mempunyai fungsi yang sama, yaitu untuk passing data, tetapi dengan menggunakan Bundle, akan terlihat lebih rapi, karena dikemas terlebuh dahulu didalam bundle sebelum dikirimkan.


# Penerapan Intent Result

1. Tampilan pada halaman utama, yang terdapat dari intent result dan tombol "EDIT NAME". tombol tersebut digunakan untuk mengedit nama yang prosesnya akan dilakukan di halaman berikutnya.

![WhatsApp Image 2021-02-25 at 22 13 29 (2)](https://user-images.githubusercontent.com/60412314/109174151-28133500-77b7-11eb-8820-ff57ef292f20.jpeg)

2. Pada halaman ini user akan memasukkan nama sesuai keinginan, kemudian terdapat button "SAVE NAME" yang digunakan unutk menyimpan perubahan nama. 

![WhatsApp Image 2021-02-25 at 22 13 29 (1)](https://user-images.githubusercontent.com/60412314/109174149-26497180-77b7-11eb-9820-1ee14ed7d0f7.jpeg)

3. Data nama yang telah di save name akan muncul pada halaman utama tadi. Dan proses edit nama, save nama akan terus berulang.

![WhatsApp Image 2021-02-25 at 22 13 29](https://user-images.githubusercontent.com/60412314/109174154-28abcb80-77b7-11eb-8d0b-531a85f5e854.jpeg)

# Kesimpulan

Intent adalah sebuah kelas dalam programming Android yang berfungsi untuk perpindahan halaman. Intent juga merupakan suatu objek yang terdapat dalam suatu activity dimana objek tersebut dapat komunikasi dengan activity yang lain, baik activity pada fungsi internal android misal seperti memanggil activity dalam satu package atau beda package yang masih berada dalam satu project. Intent Result dapat mengirim data ke activity lainnya (pindah halaman dengan membawa data) . Ada 2 cara untuk mengirimkan data/nilai antar activity didalam aplikasi Android, yaitu dengan menggunakan Intent dan Bundle, keduanya mempunyai fungsi yang sama, yaitu untuk passing data, tetapi dengan menggunakan Bundle, akan terlihat lebih rapi, karena dikemas terlebuh dahulu didalam bundle sebelum dikirimkan.

## TERIMAKASIH :)


