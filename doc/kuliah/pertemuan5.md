## Sistem Informasi Geografis - Pertemuan 5

## Create Data Geospasial

<p align="center">
  <img src="../../img/html-programming.jpg">
</p>
## Latar Belakang 
Dalam Penggunaan Sistem Informasi Geografis, masih banyak diantara kita yang belum mengetahui bagaimana cara menggunakan data pada data geospasial. Pada pertemuan ke5 Sistem Informasi Geografi ini saya akan menjelaskan bagaimana cara membuat data geospasial dengan import shapefile serta memasukkan variablenya dengan menggunakan Bahasa pemrograman phyton dan juga cara penggunaan class dan method pada python.
<br>

## Solusi 
## Membuat Data Geospasial
1. Import shapefile
<br>
2. Masukan variable, misalkan variable a untuk shapefile.writer( )
a = shapefile.writer( )
Jadi, format membuat data geospasial ada 2, yaitu :
1. .shp => Salah satu bentuk file yang terletak dalam shapefile yang menyimpan data geometri.
a.point(x,y)
a.poly [(x,y),(v,w)]
2. .dbf =>  Sebuah file yang dapat menyimpan file tabular dan menyimpan data atribut.
a.field (‘name.field’,’c’,’40’)
a.record (‘bdg’)
Data geospasial tersebut disimpan menggunakan method a.save(‘file.shp’).
Arti dari method pada writer :
- Point (x,y)           : memasukkan data berbentuk paint ke dalam .shp dan seluruh data harus berformat ESRI.1
- Poly [(a,b),(c,d)]    : memasukkan data geospasial berbentuk polygon (kembali ke titik awal) atau polyline (tidak kembali ketitik awal).
- Field (‘nama’,’c’,’40’) : artinya membuat atribut polygon dengan table ‘nama’ dengan tipe data varchar dengan panjang 40. Method ini dapat diulang dan dapat dilakukan untuk krbuthan field baru lagi.
- Record(‘Bandung’)      : Mengisi table yang hanya satu field dengan value ‘Bandung’.
- Save (‘nama.file’)  : menyimpan file dengan save file.
Kesimpulan
 format membuat data geospasial ada 2 yaitu shp : Salah satu bentuk file yang terletak dalam shapefile yang menyimpan data geometri. Dan dbf : Sebuah file yang dapat menyimpan file tabular dan menyimpan data atribut.
Saran
Live Coding dan langsung praktek bersama sama.

Nama : Muhammad Firman Kahfi
<br>
NPM : 1144015
<br>
Kelas : 3B
<br>
Prodi : D4 Teknik Informatika
<br>
Mata Kuliah : Sistem Informasi Geografis
<br>

* Link Github : https://github.com/FirmanMFK/GIS--Geographic-Information-Systems

* https://wiki.python.org/moin/BeginnersGuide
* https://www.python.org/doc/

## Scan Plagiarism

1.https://drive.google.com/file/d/0BzrCjHLyhoFsQllMSS00VTVIdFE/view?usp=sharing
2.https://drive.google.com/file/d/0BzrCjHLyhoFseUFHSUFwdjJPRlk/view?usp=sharing