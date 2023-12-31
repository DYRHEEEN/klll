# UAS PEMROGRAMAN MOBILE 
Nama &nbsp; &nbsp;: Rhendy Diki Nugraha<br>
NIM&nbsp; &nbsp; &nbsp; : 312210150<br>
Kelas&ensp; &nbsp; : TI.22.A.1<br>
Dosen &nbsp; : Donny Maulana, S.Kom., M.M.S.I.<br><br>

## KATA PENGANTAR
Alhamdulillah hirabbil 'alamin, telah sampailah kita diakhir perkuliahan dari mata kuliah pemrograman mobile-1. Di repository ini Saya bertujuan untuk menuntaskan tugas UAS dari mata kuliah tersebut. Terimakasih untuk Bapak Donny Maulana, S.Kom., M.M.S.I. selaku dosen pengampu, sekali lagi Saya mengucapkan terimakasih yang sebesar-besarnya atas bimbingan dan pelajaran yang Bapak ajarkan kepada Saya. Saya berharap, ilmu yang Bapak ajarkan dan yang Saya dapatkan dapat bermanfaat dimasa mendatang sampai yaumul akhir, Aamiin aamin yarabbal 'alamin. Langsung saja, tanpa berlama lagi, Saya akan langsung menjabarkan semua tugas kali ini.

## PERINTAH TUGAS
Perintah tugas kali ini adalah mengumpulkan semua hasil yang sudah dibuat dari pertemuan pertama sampai akhir, hasil - hasil tersebut digabungkan dalam satu Aplikasi. Berikut ini semua code yang telah Saya buat.

## PENJELASAN APLIKASI
Sebelumnya saya akan menjelaskan terlebih dahulu, ada apa saja didalam aplikasi ini. Berikut ini adalah daftarnya :
- Activity Hello World , di activity ini adalah awal dari pengenalan terhadap software Android studio. Didalam activity ini hanya terdapat kalimat yang bertuliskan "Hello_World"
- Activity Count ,  activity ini berisi program penghitungan bilangan fibonnaci yang sebelumnya telah diperintahkan untuk dibuat,
- Activity Scroll Movie , activity ini berisi sinopsis film dokumenter ICE COLD, sinopsis yang banyak digunakan untuk pembelajaran fungsi scroll didalam aplikasi android ini.
- Activity TwoActivity ,  twoactivity ini adalah sebuah program perpesanan atau chatting, yang menggunakan dua activity.
- Program Open Alarm , nah program ini berbeda dari sebelumnya, disini tidak menggunakan layout activity.xml karena program ini hanya berfungsi sebagai pembuka dan pengatur alarm dalam sebuah smartphone android.
- Program Open Map ,  sama seperti program alarm, program open map ini hanya berupa sebuah tombol yang berfungsi sebagai pembuka aplikasi google maps yang tersedia di dalam smartphone Android.
- Activity Fragment , activity ini adalah sebuah activity yang terdiri dari beberapa fragment. Disini fragmentnya berperan sebagai penampil film dengan genre yang berbeda, seperti action, comedy, dan romance.

### Semua Source Code
Disini saya tidak akan menampilkan source codenya disini, karena akan terlalu banyak dan memakan tempat dan hanya membuat pusing melihatnya. Saya sudah push semua file dari project yang sudah saya buat dan jika menginginkan bisa mendownload beberapa file yang dibutuhkan saja atau clone repository ini sepenuhnya. Sebagai gantinya, Saya hanya akan menjelaskan sedikit dari apa saja yang sudah saya kerjakan.

- Source Code Splash Launcher
  - SplashScreen.java [Lihat File](TugasUAS/app/src/main/java/com/example/tugassepuluh/SplashScreen.java)<br>
    Didalamnya berisi code java, untuk menjalankan fungsi splash launcher. Lebih jelasnya splash launcher ini adalah menampilkan gambar/logo/icon ketika kita pertama kali membuka             aplikasi, atau sebelum menuju kehalaman utama.
  - backgroundlauncher.xml [Lihat File](TugasUAS/app/src/main/res/drawable/backgroundlauncher.xml)<br>
    Ini adalah logo yang saya gunakan, Saya menggunakan logo dari channel youtube yang saya punya yaitu CREATIVEGG.
  - Hasil Run
    Berikut ini adalah hasil run nya :<br>
    
https://github.com/DYRHEEEN/Tugas-UAS-Mobile-1/assets/151630441/123f5194-2c55-4b92-a469-30ee7635af6e

<br><br>

- Source Code Utama
  - MainActivity.java [Lihat File](TugasUAS/app/src/main/java/com/example/tugassepuluh/MainActivity.java)<br>
    Di MainActivity ini berisi program java yang memiliki fungsi penghubung dari semua activity yang disebut intent dan fungsi tombol open alarm dan open map. Saya beri nama file ini         Main karena disinilah fungsi paling awal dari halaman awal.
  - activity_main.xml [Lihat File](TugasUAS/app/src/main/res/layout/activity_main.xml)<br>
    Ini adalah layout dari halaman awal aplikasi ini. Layout ini terhubung dengan MainActivity.java tadi. Dilayout ini menampilkan semua tombol tombol dari berbagai activity dan program      yang sudah dijelaskan diatas. Beginilah tampilan dari layoutnya :<br>
    ![image](https://github.com/DYRHEEEN/Tugas-UAS-Mobile-1/assets/151630441/a581874e-e647-4b21-8f19-4f90125967a3)
    > Iconnya disini sudah Saya usahakan agar sesuai dengan identitas dari activitynya.
  - AndroidManifest.xml [Lihat File](TugasUAS/app/src/main/AndroidManifest.xml)<br>
    Di AndroidManifest.xml ini berfungsi untuk mengaktifkan permission yang dibutuhkan dibeberapa activity. Selain itu, AndroidManifest.xml ini juga harus dilakukan pengeditan jika kita      menambah sebuah tombol atau activity baru yang berhubungan dengan intent, agar activity tersebut dapat dibuka nantinya.
  - string.xml [Lihat File](TugasUAS/app/src/main/res/values/strings.xml)<br>
    String.xml ini adalah sebuah values, values ini berisi teks-teks dari tombol - isi - atau apapun itu yang berhubungan dengan teks.
  - colors.xml [Lihat File](TugasUAS/app/src/main/res/values/colors.xml)<br>
    Sama seperti string, colors.xml ini juga merupakan sebuah values, tapi bedanya values ini berisi code-code warna yang sudah dibuat menjadi ID atau identitas yang bertujuan untuk          memudahkan dalam pemanggilan warnanya di dalam coding.<br><br>

- Source Code Activity Hello World
  - HelloActivity.java [Lihat File](TugasUAS/app/src/main/java/com/example/tugassepuluh/HelloActivity.java)<br>
    Disini saya tidak mengubah apapun isi dari javanya, dengan kata lain saya buat default sedari awal dibuat.
  - activity_hello.xml [Lihat File](TugasUAS/app/src/main/res/layout/activity_hello.xml)<br>
    Seperti yang sudah diketahui ini merupakan layout yang terhubung dengan java nya. Saya hanya menambahkan textview untuk menampilkan android:text "hello_world" nya (text sudah ada di      string.xml), selain itu saya juga mengubah warna text dan menambahkan background agar terlihat lebih menarik.
  - Hasil Run
    Berikut adalah hasil run nya :<br>

https://github.com/DYRHEEEN/Tugas-UAS-Mobile-1/assets/151630441/054f30de-31d8-43ca-a7d5-74ec8e0cb802

<br><br>

- Source Code Activity Count
  - CountActivity.java [Lihat File](TugasUAS/app/src/main/java/com/example/tugassepuluh/CountActivity.java)<br>
    Tentunya disini berisi code java untuk menjalankan fungsi perhitungan dari rumus fibonnaci. Bilangan fibonnaci adalah bilangan yang rumusnya adalah menambah sebuah bilangan dengan        bilangan sebelumnya. Contohnya 1, 1, 2, 3, 5, 8...
  - activity_count.xml [Lihat File](TugasUAS/app/src/main/res/layout/activity_count.xml)<br>
    Ini adalah layout dari activity count, ada beberapa tombol disini seperti set limit, count, dan reset. Angka yang ditampilkan juga sudah menggunakan code warna, agar setiap angka         yang ditampilkan memiliki warna yang berbeda dengan angka sebelumnya.
  - Hasil Run
    Berikut adalah hasil run nya :<br>

https://github.com/DYRHEEEN/Tugas-UAS-Mobile-1/assets/151630441/c80d6b3f-3c2e-4177-804d-c91675139b65

<br><br>

- Source Code Activity Scroll Movie
  - SianidaActivity.java [Lihat File](TugasUAS/app/src/main/java/com/example/tugassepuluh/SianidaActivity.java)<br>
    Disini saya tidak mengubah apapun isi dari javanya, dengan kata lain saya buat default sedari awal dibuat.
  - activity_sianida.xml [Lihat File](TugasUAS/app/src/main/res/layout/activity_sianida.xml)<br>
    Layout inilah yang mempengaruhi dan memberikan alasan kenapa di javanya tidak ada perubahan. Disini, digunakan sebuah scrollview yang bisa menjadikan text yang begitu panjang dan         tidak muat dalam satu layar penuh, maka dengan ini kita bisa membaca semua isi kontennya hanya dengan cara scroll layar.
  - Hasil Run
    Berikut adalah hasil run nya :<br>

https://github.com/DYRHEEEN/Tugas-UAS-Mobile-1/assets/151630441/70779eef-1c2f-4886-9f51-d310ac4d0125

<br><br>
