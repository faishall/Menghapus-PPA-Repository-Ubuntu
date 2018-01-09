# Cara Menghapus PPA Repository Ubuntu Linux
PPA atau Personal Package Archive merupakan repository yang dapat dibuat oleh setiap orang yang ditempatkan pada Launchpad server agar bisa diakses secara global oleh setiap orang di seluruh belahan dunia. PPA memudahkan kita menginstal software yang tidak atau belum disertakan secara resmi pada repository Ubuntu. 

# Menghapus PPA repository

Ubuntu Linux selain memiliki perintah untuk menambahkan PPA repository juga menyediakan cara menghapusnya yakni dengan menambahkan atribut --remove kemudian diikuti nama PPA dan subdirektori atau PPA itu sendiri. Contoh perintahnya adalah:

`sudo add-apt-repository --remove ppa:nama-ppa/ppa`


![xx](http://3.bp.blogspot.com/-VzBC2SdR2nk/UAS_ev6WriI/AAAAAAAAAE4/UAMDpfg8A0g/s400/repository-remove.png)

# Alternatif lain menghapus PPA repository

Selain menggunakan perintah CLI (Command Line Interface) seperti di atas, Anda juga dapat dengan mudah menghapus PPA repository melalui antarmuka GUI (Graphical User Interface). Untuk menghapus PPA repository dengan cara ini pada Ubuntu Linux versi 12.04, jalankan Ubuntu Software Center. Kemudian pada menu `Edit` pilih submenu `Software Sources`. 

![xx](http://1.bp.blogspot.com/-3zmL_fX88Y4/UAS_sVVBRxI/AAAAAAAAAFE/DHUtkRab9Rc/s400/software-sources-ubuntu-12.04.png)


## Menghapus source file PPA repository
Selain kedua cara yang telah disebutkan di atas, masih ada cara lagi yakni menghapus source file PPA repository. File ini diletakan pada direktori /etc/apt/sources.list.d. Hapuslah source file PPA repository tersebut. Jika Anda tidak mengetahui nama filenya, Anda bisa gunakan perintah ls untuk melihat daftar file yang ada di direktori tersebut. 

![xx](http://4.bp.blogspot.com/-yDDalXQ6GAw/UAS_72S-k1I/AAAAAAAAAFQ/Z9clFjd7Ni4/s400/sources.list.d.png)

