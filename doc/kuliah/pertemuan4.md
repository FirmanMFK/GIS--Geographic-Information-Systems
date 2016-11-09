## Sistem Informasi Geografis - Pertemuan 4

##  RETRIVE DATA GEOSPASIAL

<p align="center">
  <img src="../../img/Python-Gis.jpg">
</p> 

LATAR BELAKANG MASALAH
Retrieve Data Geospasial ialah Meretrieve Data Vektor.

Geometri Data koordinat yang membentuk bangun datar/ruang diantaranya:

1.Point/titik [1]
<br>
2.Line/garis [3] Shape,type
<br>
3.Polygon [5]
<br>

## Terdapat 3 geometri standar ESRI

1.Point
<br>
2.Poline
<br>
3.Poligon
<br>


## Operasi pada Pyhton

Library pyshp yaitu adalah IMPORT SHAPFILE penjelasan instansi kelas shapfile kepada sebuah variable

Sf = shapefile.Reader(‘Bts.shp’)

Penjelasan :

SF = Variable

Shapfile = Sebuah class

Reader = Method

Bts,shp = Parameter file

Method method pada data DBF dan SHP

Method pada data DBF

sf.fileds() adalah untuk melihat attribute table

sf.records() adalah untuk mengambil semua record

sf.record(n) adalah untuk isi record

Method pada data SHP

Sf.shapes() adalah untuk mengambil semua record geometri

Sf.shape(n) adalah untuk mengambil 1 record pada baris n
Cara untuk mengambil 1 record dengan parameter nilai atau Array

sf.records(0) [8]

sf.field(0) [8]

Titik koordinat terdapat 4 titik

BBOX

POINT

SHAPETYPE

Contoh Code untuk menampilkan nama Negara memakai contruk .

For a in sf.records():

If a[8] = “Indonesia””

Print a

Atau bisa juga

I = 0

For a in sf.records():

If a[8] ==”Zimbabwe”:

Print a :

I = i+1


# Praktikum

Menampilkan jumlah record melalui terminal

<p align="center">
  <img src="../../img/praktikum4/satu.png">
</p> 

Masukan Kode didalam tugas.py

<p align="center">
  <img src="../../img/praktikum4/tiga.png">
</p>

Membuat  Method Select, Where Negara Indonesia Output Data Record Negara Indonesia

<p align="center">
  <img src="../../img/praktikum4/dua.png">
</p>

## Kesimpulan 

Dengan membuat class di python yang sesuai dengan file.py akan membuat  kita bisa melihat record data.
Dengan perintah perintah yang sudah dipraktekan kita menjadi lebih tahu hal hal yang baru di Python. 

## Saran
Pengembangan GIS untuk User dan bagaimana penerapannya dgn bahasa python harus dipraktekan.

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
