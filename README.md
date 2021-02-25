# Fragment
 Materi Android Fragment dengan Butterknife

 Program Fragment ini dibuat dengan menggunakan library Butterknife
![Screenshot_2021-02-25-20-48-01-301_com dycode edu fragment](https://user-images.githubusercontent.com/60208227/109163491-f9dc2800-77ab-11eb-88df-bfb2fd118eea.jpg)

![Screenshot_2021-02-25-20-48-05-439_com dycode edu fragment](https://user-images.githubusercontent.com/60208227/109163495-fc3e8200-77ab-11eb-9565-23b37e117264.jpg)

#### Beberapa penjelasan seputar Fragment
- Fragment merupakan salah satu komponen pada Android Studio dengan fungsi yang hampir sama seperti activity tetapi memiliki “lifecycle” yang berbeda.
- Fragments merupakan content controllers dan memiliki view, layout, serta event logic sendiri
- Lifecycle pada Fragment 
 ![images](https://user-images.githubusercontent.com/60208227/109165505-36a91e80-77ae-11eb-853f-08e0293fec50.png)
- OnAttach, saat sebuah fragment dipanggil sebuah activity
- OnCreate, dipanggil untuk pembuatan awal fragment
- OnCreateView, memanggil karna saat itu sistem sedang menggambar fragment pertama kali
- OnActivityCreated, dipanggil ketika activity telah selesai dengan method onCreate
- OnStart, dipanggil karna fragment telah siap untuk didisplay atau ditampilkan di layar
- OnResume, digunakan untuk membuat fragment interaktif.
- OnDetach, fragment tidak terikat dengan activity, dan tidak memiliki hirarki view lagi.
- OnDestroy, dipanggil setelah fragment tidak digunakan, masih ada objek java melekat pada activity.
- OnDestroyView, dipanggil setelah hirarki view fragment tidak lagi dapat diakses.
- OnStop, digunakan jika fragment tidak lagi  terlihat.
- OnPause, sistem akan memanggil metode ini sebagai indikasi pertama bahwa pengguna sedang meninggalkan fragmen(walau itu tidak selalu berarti fragmen sedang dimusnahkan)

Demikian yang bisa saya sampaikan semoga berhasil saat mencobanya!
