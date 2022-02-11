# Rangkuman Video 5

<p>&nbsp;</p>

## Penulis:
### Yosep Putra Setiyanto
### 13320026

<p>&nbsp;</p>
<p>&nbsp;</p>

##  Bekerja dengan git
.
### Gambaran Umum

bekerja dengan git namun bila pada video video sebelumnya menggunakan github kali ini kita akan menggunakan terminal atau konsol.    
.     
### 3 area pada repository git :
- working tree : folder tempat kita bekerja
- staging area : tempat ketika telah melakukan perubahan
- history : tempat setelah kita melakukan commit  

bila kita telah membuat repository, maka folder tersebut akan menjadi repository, dan git akan memantau apakah ada perubahan pada file file didalamnya, bila terdapat perubahan maka kita dapat melakukan "git add"dan masuk ke staging area. selanjutnya bila selesai melakukan perubahan dan melakukan "git commit" maka akan masuk ke area history.  
.
### Menggunakan Fork

- langkah pertama yang dapat dilakukan untuk bekerja dengan git adalah mengisntall aplikasi git, kita dapat dengan mudah mendownloadnya pada laman resmi git sesuai dengan sistem operasi pc kita. selanjutnya install sesuai dengan prosedur penginstallan aplikasi pada umumnya. 
- bila selesai menginstall aplikasi git maka untuk memulai kita harus mebentuk working tree kita. untuk mengubah suatu folder pada pc kita menjadi repository kita dapaet mengetikan perintah

```
cd <path folder>
git init
```

maka folder tersebut akan menjadi repository didalam git dan semua perubahan didalamnya akan diawasi oleh git
### contoh screenshot:
![](screenshots/.png)
 
- untuk melihat apakah ada file yang belum tercommit dalam github kita dapat mengetikan
 
 ```
git status 
```
### contoh screenshot:
![](screenshots/.png)
 
- untuk menambahkan file yang belum ter-track ke dalam stagging area maka kita dapat menggunakan perintah

```
git add <nama file>
```

atau untuk banyak file sekaligus

```
git add .
```
### contoh screenshot:
![](screenshots/.png)
 
- kemudian setelah masuk ke stagging area maka kita dapat melakukan commit dengan cara 

```
git commit -m "<judul commit>"
```

- maka setelah semua file telah dicommit maka akan tertulis "nothing to commit, working tree clean"   
### contoh screenshot:
![](screenshots/.png)
 
- untuk melihat catatan rekaman perubahan kita dapat mengetikan perintah 

```
git log -<berapa log terakhir yang ingin dilihat>
```
### contoh screenshot:
![](screenshots/.png)
 
<p>&nbsp;</p>