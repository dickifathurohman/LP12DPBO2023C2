# LP12DPBO2023C2

## Janji

Dicki Fathurohman_2103842_Ilmu Komputer LP12 DPBO2023

Saya Dicki Fathurohman [2103842] mengerjakan LP12 DPBO2023 dalam mata kuliah DPBO, untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikan. Aamiin.

## Alasan

Menggunakan mvvm karena view tidak berhubungan dengan model.

Pada program ini akan mengakses view yaitu Synchronization.java, yang akan mengakses viewmodel yaitu Game.Java, dimana viewmodel ini akan mengakses model untuk mengambil data. Sehingga view tidak berhubungan langsung dengan file model untuk mandapatkan data. Game.java, Handler dan Controller.java merupakan viewmodel karena file-file tersebut akan mengakses model yang ada. Model terdiri dari display, gameInterface, GameObject, dan Player karena file-file tersebut merupakan class yang menginisiasi diri mereka sendiri.

## Perbedaan LP dan TMD

Pada LP file `Display` yang berfungsi untuk menampilkan permainan disimpan di model. Sedangkan pada TMD yang dibuat, fungsi untuk menampilkan game disimpan di view karena dia hanya berfungsi untuk menampilkan game, tidak berfungsi untuk menampung atau mengstore data, yaitu file `GameWindow` yang akan memanggil `Game` pada viewmodel. Alasan dari penyimpanan `Game` pada viewmodel ini karena pada `Game` dia memiliki method/fungsi untuk setter getter untuk mengstore data tidak hanya sekedar menampilkan tampilan game.
`Game Interface` tidak digunakan pada TMD ini, untuk render terdapat pada viewmodel.
Pada struktur TMD yang dibuat controller sudah dipisahkan tidak menyatu lagi, sehingga controller untuk player, score dan pijakan (Foothold) memiliki file tersendiri agar lebih mudah untuk diimplementasikan dan ketika perlu modifikasi untuk model tertentu hanya cukup mengubah satu file controller. 
