# Rangkuman Video 3

<p>&nbsp;</p>

## Penulis:
### Yosep Putra Setiyanto
### 13320026

<p>&nbsp;</p>
<p>&nbsp;</p>

## Branch
.  
### Gambaran Umum
- secara otomatis branch awal ketika membuat repository adalah master brach atau cabang utama. 

- Sedangkan branch baru dibuat ketika kita untuk membuat fitur baru namun masih belum yakin akan fitur ini jadi tidak mau mengganggu jalur utama.kita belum tahu apakah fitur tersebut akan diterapkan atau tidak apakah fitur tersebut akan diselesaikan atau tidak. Bila tidak jadi diterapkan atau tidak selesai maka jalur utama tidak perlu diubah lagi dan branch dapat dihapus namun bila akan diterapkan maka dapat dilakukan merging dengan jalur utama. 

- selain itu dalam bekerja berkelompok dapat menggunakan branch untuk setiap anggota kelompok, yang nantinya setiap pekerjaan anggota kelompok dapat di merging dengan jalur utama dan terkumpul hasil pekerjaan bersama  
.  
### Membuat Branch Baru
Untuk membuat branch, pada bagian repository kita , piilih dibagian branches, pilih branch yang akan dituju bila sudah aada brach namun bila belum ada branch maka kita dapat membuat branch baru dengan cara mengetikan nama branch baru kita lalu pilih crate branch:"nama branch baru" 

### . 
### menggunakan branch 
- ketika mengedit atau mebuat file maka ketika melakukan commit akan otomatis tersimpan ke dalam branch baru
- bila kita melihat pada visualisasi commit maka kali ini terdapat visualisasi sebuah cabang baru dibawah jalur utama.
- bila kitaa telah merasa cocok amka kita dapat melakukan merging ke jalur utmaa dengan cara memilih "compare & pull request" mka kita akan dialihkan ke halaman "open a pull request" github akan meverifikasi apakah kedua branch dapat di merging secara otomatis atau tidak bila tidak akan disebut merge conflict. 
- bila branch tidak dapat dilakukan merging secara otomatis maka akan ada tertulis "can't automatically merge. Dont't worry you can still create the pull request" yang artinya walau terdapat kocflik namun kita tetap dapat melakukan pull request.

- disebut pull request karena kita harus minta izin ke pemilik master untuk menarik perubahan yang telah kita buat ke jalur utama karena siapa tau nanti kita membuat branch dari file orang lain. 
- bila telah selesai lalu pilih "create pull request". 
- dihalaman pemilik repository maka akan muncul pull request, bila tidak terdapat konflik maka kita dapat langsung memilih "merge pull request", namun bila terdapat konflik maka tobol tersebut belum ada dan ada peringatan "this branch hahs conflicts that must be resolved" dan pemilik repositorylah yang harus meresolve atau menyelesaikan konflik tersebut dengan cara pilih "resolve conflict" 
- maka kita akan diarahkan ke kode editor dimana bagian yang ada konflik akan otomatis ditandai dengan warna merah disampingnya selain itu juga kita dibverikan pilihan antara kedua branch yang setiap pilihan dibatasi dengan "<<<< dan ===== dan juga >>>>>" untuk meresolve hapus bagian yang tidak kita pilih, maka konflik sudah selesai dan merging dapat kita confirm merge, maka kedua branch selesai kita gabungkan.

<p>&nbsp;</p>