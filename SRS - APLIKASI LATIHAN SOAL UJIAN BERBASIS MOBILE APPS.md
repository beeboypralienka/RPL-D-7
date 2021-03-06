## **SOFTWARE REQUIREMENTS SPECIFICATION**

Version 1.0

22 Februari 2018

![](POLINDRA.png)

​					APLIKASI LATIHAN UJIAN BERBASIS MOBILE APPS

​						Disusun Oleh :

​							Bahrainsyah Oksareinaldi (1603092)

​							Dodi Hodayat (1603095)

​							Muhroz Al Farizi (1603108)

​							Syahrul Romadoni (1603114)

​								D3 Teknik Informatika

​							  Politeknik Negeri Indramayu

#### SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK

1. **Pendahuluan**

   ​	Pada bagian ini memberikan deskripsi dan gambaran mengenai apapun yang terdapat pada dokumen SRS. Juga tujuan dari pembuatan dari dokumen ini di gambarkan dan di urutkan juga didefinisikan.

   **1.1	Tujuan**

   ​	Tujuan dari pembuatan dokumen ini adalah untuk memberikan detail dari System Requirement dari "Aplikasi Latihan Ujian Nasional Berbasis Mobile Apps". Pada dokumen ini mengilustrasikan tujuan dan pernyataan lengkap dari pembuatan sistem. Dokumen ini juga menjelaskan spesifikasi system, interface dan hubungan dengan aplikasi lainnya.

   **1.2	Lingkup**

   ​	"Aplikasi Latihan Ujian Berbasis Mobile Apps" merupakan sebuah aplikasi mobile yang dibuat bekerja sama dengan mitra yaitu SMK RISTEK MULTIMEDIA Indramayu. Pada aplikasi ini disediakan materi, latihan soal dan soal - soal yang diharapkan dapat meningkatkan mutu dari siswa - siswa dalam kompetensinya.

   Batasan dari aplikasi ini ialah pada soal - soal dan materi, hanya berkaitan dengan bidang multimedia dan beberapa materi pelajaran wajib. Pada aplikasi inipun disediakan juga fitur live chat antar sesama siswa. Juga disediakan fitur perangkingan berbasis grafik.

   **1.3	Definisi, Akronim, Singkatan**
-    Mobile Apps : Aplikasi perangkat bergerak meliputi IOS, Android.
	    Firebase	 : Database realtime dari google yang tidak berbasis DBMS.
	    Live Chat	 : Merpakan aplikasi Chatting yang up to date terhadap perubahan dalam waktu maksimal 5 detik.


   **1.4	Referensi**
-    Software Requirements Specification, "Web Publishing System", April 15, 2004.

-    IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements
  Specifications. IEEE Computer Society, 1998.

   **1.5	Overview**
   Didalam dokumen ini memuat 3 bab yang masing - masing bab menjelaskan fungsi dan desain darri aplikasi latihan ujian berbasis mobile apps. Pada bab 1 menjelaskan tentang tujuan, lingkup, definisi singkatan, referensi pembuatan dokumen ini dan gambaran tentang dokumen ini.
   Pada bab ke-2 menjelaskan tentang gambaran dari produk yang akan dibuuat, interface yang digunakan, btasan memory dan operasi - oerasi yang ada pada sistem.
   Pada bab ke-3 menjelaskan tentang spesifikasi yang terdapat pada sistem ini.

  **2.	Gambaran Umum**

   **2.1 Perspektif Produk**

   ​	Aplikasi Latihan Ujian Berbasis Mobile Apps bertujuan untuk sekolah-sekolah yang masih belum memiliki fasilitas sekolah yang memadai terutama di bagian fasilitas komputer dan alat-alat electroniklainya, dan juga terutama untuk siswa/siswi yang masih belum memiliki komputer/laptop di rumahnya maka dari itu aplikasi ujian berbasisi mobile ini siswa/siswi bisa latihan ujian nasional dimana saja dan kapan saja karna latihan ujian nasional ini berbasis android yang bisa dibawa kemana saja oleh siswa/siswi.

   ​	**2.1.1	Antarmuka Sistem**

   	**2.1.2	Antarmuka Pengguna (MOCKUP)**

  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png) |
  | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png) |
  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image018.png) |
  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image020.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image022.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png) |
  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image026.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image028.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image030.png) |
  | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image032.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image034.png) | ![img](file:///C:/Users/RPL-19/AppData/Local/Temp/msohtmlclip1/01/clip_image036.png) |

   ​	**2.1.3	Antarmuka Perangkat Keras**

   ​	Antarmuka komunikasi Aplikasi Latihan Ujian Berbasis Mobile Apps ini sang (User) pengguna harus memiliki setidaknya smartphone minimal android versi 4.0.3 (Ice Cream Sandwich) untuk menginstall aplikasi ini.

   ​	**2.1.4	Antarmuka Perangkat Lunak**

   ​	Aplikasi Latihan Ujian Berbasis Mobile Apps ini hanya bisa di instal di android versi 4.0.3 (Ice Cream Sandwich) karna simulasi aplikasi ujian ini bisa di jalankan hanya untuk ver 4 ke atas tidak bisa android ver 4 kebawah.

   ​	**2.1.5	Antarmuka Komunikasi**

   ​	Antarmuka komunikasi Aplikasi Latihan Ujian Berbasis Mobile Apps ini admin dan user harus tersambung internet terutama untuk admin untuk mengupload materi pelajaran dan menginputakan data seperti menabah materi-materi pelajaran dan mengupload ujian dan latihan ujian yang akan di jalankan oleh siswa/siswi, Dan user tidak harus online si user hanya bisa ujian, latihan ujian dan mendownload meteri-materi pelajaran yang di upload oleh si guru.

   ​	**2.1.6	Batasan Memory**

   ​	**2.1.7	Operasi -Operasi**

   ​	

  | No   | Tampilan                          | Operasi                      | Fungsi                                                       |
  | ---- | --------------------------------- | ---------------------------- | ------------------------------------------------------------ |
  | 1    | Tampilan Login                    | Input Email                  | Berfungsi sebagai ID akun masuk ke aplikasi.                 |
  | 2    |                                   | Input Password               | Berfungsi sebagai security ID akun aplikasi anda.            |
  | 3    |                                   | Button Login                 | Berfungsi sebagai proses masuk aplikasi.                     |
  | 4    |                                   | Button Forget                | Berfungsi sebagai ketika user tidak tahu passwordnya atau lupa password. |
  | 5    | Tampilan Lupa Password            | Input Username               | Berfungsi sebagai ID username security yang ada di databases. |
  | 6    |                                   | Input Nomer HP               | Berfungsi sebagai ID nomer security yang ada di databases.   |
  | 7    |                                   | Input Email                  | Berfungsi sebagai ID email security yang ada di databases.   |
  | 8    |                                   | Button Canlce                | Berfungsi sebagai tidak jadi untuk lupa password.            |
  | 9    |                                   | Button Send                  | Berfungsi sebagai mengirim data yang telah di input oleh user, jika benar  buttom ini akan mengarah ke rubah password jika tidak buttom ini akan kembali  ke tampilan lupa password. |
  | 10   | Tampilan Rubah Password Dll       | Input Password               | Berfungsi sebagai perubahan password yang tadi lupa jadi biki lagin  dengan akun yang sama, yang telah di inputkan di Tampilan Lupa Password. |
  | 11   |                                   | Input Nomer HP               | Berfungsi sebagai perubahan nomer hp biasanya nomernya udah muncul, jika  mau dirubah nomernya silahkan ganti nomernya jika tidak dirubah maka jangan  dihapus atau dirubah. |
  | 12   |                                   | Input Email                  | Berfungsi sebagai perubahan email atau jika mau dirubah silahkan dirubah  jika tidak dirubah jangan dihapus atau dirubah emailnya. |
  | 13   |                                   | Button Cancle                | Berfungsi sebagai buttom ini akan mengarahkan ke halaman Tampilan Login  atau buttom ini membatalkan perubahan password baru. |
  | 14   |                                   | Button Send                  | Berfungsi sebagai perubahan databases, buttom ini yang akan mengarahkan  ke databases kalo ada Password, NoHp dan Email yang ada di rubah |
  | 15   | Tampilan Register                 | Input Email                  | Berfungsi sebagai ID login untuk ID masuk ke aplikasi.       |
  | 16   |                                   | Input Password               | Berfungsi sebagai Password security ID akun aplikasi anda.   |
  | 17   |                                   | Button Cancle                | Berfungsi sebagai tidak jadi untuk register buttom ini akan mengarahkan  ke Tampilan Login. |
  | 18   |                                   | Button cread                 | Berfungsi sebagai membuat akun atau ID baru di aplikasi.     |
  | 19   |                                   | Icon GooglePlus              | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari Google. |
  | 20   |                                   | Icon Facebook                | Berfungsi sebagai membuat akun atau ID baru di aplikasi tapi menggunakan  akun dari facebook. |
  | 21   | Tampilan Awal Aplikasi            | Icon 3 Garis Horizon         | Berfungsi sebagai buttom fitur tambahan yang ada di Tampilan Awal  Aplikasi fitur tamabahanya itu editting profile user dll. |
  | 22   |                                   | Button Icon Buku             | Berfungsi sebagai buttom yang akan mengarahkan ke bacaan buku yang ada di  aplikasi tersebut. |
  | 23   |                                   | Button Icon latihan          | Berfungsi sebagai buttom yang akan mengarahkan ke latihan ujian yang  sudah di pelajari dan akan muncul di soal Ujian. |
  | 24   |                                   | Button Icon Ujian            | Berfungsi sebagai buttom yang akan meagarahkan ke Simulasi Ujian asli  yang akan muncul di Ujian Online. |
  | 25   |                                   | Button Icon Static           | Berfungsi sebagai buttom yang akan mengarahkan ke static grafic latihan  ujian dan rangking yang sudah di kerjakan. |
  | 26   |                                   | Button Icon Chatting         | Berfungsi sebagai chatting user, fitur ini bisa digunakan untuk chatting  sesama userlain yang dapat di diskusian bersama userlain dan bisa membuat  group user. |
  | 27   |                                   | Button Icon Setting          | berfungsi sebagai mengatur pengaturan yang ada di aplikasi tersebut. |
  | 28   |                                   | Button Icon About            | Berfungsi sebagai yang akan mengarahkan informasi aplikasi.  |
  | 29   | Tampilan Buku                     | Button icon buku             | Berfungsi sebagai buku pelajaran yang bisa dibaca lewat hp selain buku  normal biasanya. |
  | 30   | Tampilan Statistic                |                              | Berfungsi sebagai melihat grafic statistic ujian, latihan,rangking dll. |
  | 31   | Tampilan About                    |                              | Berfungsi sebagai menampilkan informasi aplikasi seperi aplikasi servi  berapa, dibuat siapa dll. |
  | 32   | Tampilan Chatting                 | Button Priver Cahtting       | Berfungsi sebagai private chattting (Chat) sesama user.      |
  | 33   |                                   | Button Group Chatting        | Berfungsi sebagai group chatting (chat) ke semua user yang sudah  ditambahkan ke group chatting tersebut. |
  | 34   | Tampilan Setting                  |                              | Berfungsi sebagai menampilkan settingan beberapa penganturan yang mau  akan dirubah oleh user. |
  | 35   | Tampilan Latihan Ujian            | Timedown                     | Berfungsi sebagai menampilakan waktu yang akan diujian oleh latihan ujian  aplikasi. |
  | 36   |                                   | Button Icon Play             | Berfungsi sebagai akan dimulainya latihan ujian.             |
  | 37   |                                   | Button icon pause            | Berfungsi sebagai mulai laginya ujian yang sudah pause sebelunya pada  saata latihan ujian sedang berlangsung. |
  | 38   | Tampilan saat mulai latihan ujian | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
  | 39   |                                   | Button icon pause            | Berfungsi sebagai di pausenya latihan ujian untuk memberhentikan  sementara time down latihan ujian dan akan mengarahkan ke tampilan Mulai  latihan ujian. |
  | 40   |                                   | Button icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
  | 41   |                                   | Button icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
  | 42   | Tampilan selesai latihan ujian    | Button icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
  | 43   |                                   | Button icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
  | 44   | Tampilan ujian                    | Timedown                     | Berfungsi sebagai jangka waktu pengerjaan ujian latihan.     |
  | 45   |                                   | Buttom Icon Play             | berfungsi sebagai mulainya ujian.                            |
  | 46   | Tampilan saat mulai Ujian         | Timedown                     | Berfungsu sebagai waktu mundur yang sedang berjalan.         |
  | 47   |                                   | Button icon panah kanan/kiri | Berfungsi sebagai menggati soal yand ada di latihan ujiantersebut. |
  | 48   |                                   | Button icon Pilihan          | Berfungsi sebagai pilihan jawan user.                        |
  | 49   | Tampilan selesai ujian            | Button icon ya               | Berfungsi sebagai jika jawaban sudah fik buttom ini akan mengarahkan ke  Tampilan Awal Aplikasi. |
  | 50   |                                   | Button icon tidak            | Berfungsi sebagai jika jawaban salah maka buttom ini akan mengarahkan ke  tampilan mulai ujian atau kembali mengerjakan latihan ujian. |
  | 51   | Tampilan Pilih Latihan Ujian      | Button icon Pilihan Ujian    | Berfungsi sebagai memilih latihan soal ujian yang akan dipilih. |
  | 52   | Tampilan Pilih Ujian              | Button icon Pilihan Ujian    | Berfungsi sebagai memilih soal ujian yang akan dipilih.      |
  | 53   | Tampilan Lihat Buku               |                              | Berfungsi sebagai menampilkan buku pelajaran.                |
  | 54   | Tampilan Tambah Chatting Private  | Button chatting              | Interaksi user dan user yang sedang dijalan.                 |
  | 55   |                                   | Button Tambah Chatting       | Berfungsi sebagai menabha kontak baru dari private chatting. |
  | 56   |                                   | Button kurang chatting       | Berfungsi sebagai mengurangi beberapa kontak  Chatting Private. |
  | 57   | Tampilan Tambah Chatting group    | Button chatting Group        | Interaksi user dan user yang sedang dijalan.                 |
  | 58   |                                   | Button Tambah Chatting Group | Berfungsi sebagai menabha kontak baru dari group chatting.   |
  | 59   |                                   | Button kurang chatting       | Berfungsi sebagai mengurangi beberapa kontak group chatting. |
  | 60   | Tampilan Profile                  | Button Back                  | Berfungsi sebagai kembali ke Tampilan Awal Aplikasi.         |
  | 61   |                                   |                              | Menampikan informasi user.                                   |
  | 62   |                                   | Button Setting               | Berfungsi sebagai mengedit Profile user.                     |
  | 63   | Tampilan EditUser                 | Button Back                  | Berfungsi kembali ke Tampilan Profile.                       |
  | 64   |                                   | Input Username               | Berfungsi sebagai merubah username.ke databases.             |
  | 65   |                                   | Input Password               | Berfungsi sebagai merubah password ke databases.             |
  | 66   |                                   | Input Email                  | Berfungsi sebagai merubah email ke databases.                |
  | 67   |                                   | Input Nomer HP               | Berfungsi sebagai merubah nomer hp ke databases.             |
  | 68   |                                   | Input Alamat                 | Berfungsi sebagai merubah alamat ke databases.               |
  | 69   |                                   | Input Ayah                   | Berfungsi sebagai merubah nama orang tua ayah ke databases.  |
  | 70   |                                   | Input Ibu                    | Berfungsi sebagai merubah nama orang tua ibu ke databases.   |
  | 71   |                                   | Input Nomer HP Orangtua      | Berfungsi sebagai merubah nomer orang tua ayah/ibu ke databases. |

   **2.2	Spesifikasi Kebutuhan Fungsional**

   **2.3	Spesifikasi Kebutuhan Non-Fungsional**

   **2.4	Karakteristik Pengguna**

   **2.5	Batasan - Batasan**

  Batasan dari Aplikasi Latihan Ujian Berbasis Mobile Apps ini  masih di lingkup wilayah di daerah indramayu terutama aplikasi ini masih  buat mitra SMK Ristek Lohbener indramayu dan juga aplikasi ini masi  dalam tahap pengujian dan masih belum di sebarluaskan.

   **2.6	Asumsi - Asumsi Keterkaitan**

  **3.		Requirement Specification**


   ​

   ​