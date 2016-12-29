## Sistem Informasi Geografis - Pertemuan 6

<p align="center">
  <img src="../../img/images.jpg">
</p>
#Instalasi Map Server
<h3>Langkah Pertama</h3> 
1.Install VirtualBox
2.Install Centos 6.8
3.Python.

<h3>Langkah Kedua</h3>
1.Add Repo epel & elgis
.#rpm-uvh http://downloadfedoraproject.org/pub/epel/6/x86_64/epel:release.6.8.noeurch.rpm
.#rpm uvh http://elgi.argeo.org/repos/6/elgis/-release-6-6-0/noeuroh.rpm
<br>
2.exclude = armadillo dan edit file
.#vi/etc/yum.repos.d/epel.repo 
tambahkan exclude = armadilo
<br>
3.Instalasi armadillo
.#wget http://elgis.argeo.org/repo/6/elgis/x86_64/gda1-1.9.2-4.ei6.X86_64.rpm
.#yum install armadillo-3.80002-1/e;6/X86_64.rpm
<br>
4.Install depedensi
<br>
.#yum install gpsbabel
<br>
.#yum install gdal
<br>
.#yum install mapserver
<br>
.#yum install glibc
<br>
.#yum install libpng libpng libpng-devel
<br>
.#yum install giflib-devel
<br>
.#yum install prog-epsg
<br>
5.Selesai cek Instalasi
.#rpm-almapserver

<br>
Instalasi MapProxy
.#yum install Python-pip python devel.
<br>
.#pip install mapproxy 
<br>
.#install vwsql
<br>
.#pip install vwsql

di Halaman.download 
unduh peta indonesia sudah termasuk mapfile,shp & mapproxy

atau di kambing.ui.ac.id/iso/centos 

demo via map.vas.web.id/demo

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
* kambing.ui.ac.id/iso/Centos

## Scan Plagiarism

1.https://drive.google.com/file/d/0BzrCjHLyhoFsQllMSS00VTVIdFE/view?usp=sharing
2.https://drive.google.com/file/d/0BzrCjHLyhoFseUFHSUFwdjJPRlk/view?usp=sharing