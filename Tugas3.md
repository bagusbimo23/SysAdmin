<div align="center">
  <h1 style="text-align: center;font-weight: bold">LAPORAN WORKSHOP ADMINISTRASI JARINGAN<br>Tugas 3</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : <br>Kelompok 1</h3>
  <p style="text-align: center;">
    <strong>Mahendra Khibrah Rabbani Sayyid (3122500013)</strong><br>
    <strong>Akmal Zidani Fikri (3122500019)</strong><br>
    <strong>Bagus Bimo Prakoso (3122500028)</strong>
  </p>

<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
<hr>
<hr>
</div>

## 1. Mencoba Install Package Eksternal - GDebi - DPKG

Intstall gdebi menggunakan apt
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.001.png)
<<<<<<< HEAD
<br>
=======
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Pilih package .deb lalu pilih untuk install melalui gdebi
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.002.png)
<<<<<<< HEAD
<br>
=======










>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Pada tampilan gdebi klik untuk install package
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.003.png)
<<<<<<< HEAD
<br>
=======
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Sebelum install, kita akan dimintai untuk memasukkan password user
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.004.png)
<<<<<<< HEAD
<br>

Berikut adalah proses instalasi dari .deb file
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.005.png)
<br>
=======

Berikut adalah proses instalasi dari .deb file![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.005.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Kita bisa menghapus package dengan menekan menu dari remove package
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.006.png)
<<<<<<< HEAD
<br>
=======






>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

**DPKG**
<br>

Install deb file menggunakan dpkg di cli
<br>

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.007.png)
<<<<<<< HEAD
<br>
=======
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Jika terdapat error maka install satu per satu dependency yang diperlukan menggunakan apt
<br>

Untuk menghapus package deb bisa menggunakan command
`dpkg –purge nama_package`
<br>

<br>

<<<<<<< HEAD
## 2. Setting Mikrotik Lab Jaringan PENS
=======
Buka WinBox dan pastikan terhubung dengan LAN Mikrotik. 
Menghubungkan MAC Address Mikrotik dengan mode Legacy.![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.008.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

### Topologi

![](images/tugas3/0.png)

<<<<<<< HEAD
Buka WinBox dan pastikan terhubung dengan LAN Mikrotik.
Menghubungkan MAC Address Mikrotik dengan mode Legacy.
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.010.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

![](images/tugas3/1.png)

<<<<<<< HEAD
<br>
Set IP Address baru untuk ethernet 1 dengan masuk ke menu IP Address.
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.011.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

![](images/tugas3/2.png)
![](images/tugas3/3.png)

IP Baru berhasil ditambahkan
<br>

![](images/tugas3/4.png)

Set Bridge
<br>

<<<<<<< HEAD
![](images/tugas3/5.png)
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.012.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Buat bridge baru
<br>

<<<<<<< HEAD
![](images/tugas3/6.png)
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.013.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Bridge berhasil ditambahkan.
<br>

<<<<<<< HEAD
![](images/tugas3/7.png)
<br>
Pindah ke tab submnu ports untuk menambahkan port secara manual,
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.014.png)Pindah ke tab submnu ports untuk menambahkan port secara manual,
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5
untuk port ether2,3,4,5 agar menjadi satu switch bridge.
<br>

<<<<<<< HEAD
![](images/tugas3/8.png)
<br>

![](images/tugas3/9.png)
<br>

![](images/tugas3/10.png)
<br>

![](images/tugas3/11.png)
<br>

![](images/tugas3/12.png)
<br>

![](images/tugas3/13.png)
<br>

![](images/tugas3/14.png)
<br>

![](images/tugas3/15.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.015.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.016.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.017.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.018.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.019.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.020.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.021.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.022.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Setelah set bridge dan menyatukan port ether2,3,4,5 menjadi satu switch,
selanjutnya tambahkan ip address untuk port yang jadi satu tadi.
<br>

![](images/tugas3/16.png)
<br>

<<<<<<< HEAD
![](images/tugas3/17.png)
<br>

![](images/tugas3/18.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.023.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.024.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Setelah itu set route, agar bisa tersambung ke gateway
<br>

<<<<<<< HEAD
![](images/tugas3/19.png)
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.025.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

<br>
Ini default setelah set IP pada step sebelumnya
<br>

<<<<<<< HEAD
![](images/tugas3/20.png)
<br>

![](images/tugas3/21.png)
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.026.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.027.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Route ke gateway berhasil ditambahkan
<br>

<<<<<<< HEAD
![](images/tugas3/22.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.028.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Selanjutnya set DHCP, agar setiap device yang connect mendapatkan IP secara otomatis atau dinamis.
<br>

<<<<<<< HEAD
![](images/tugas3/23.png)
<br>

![](images/tugas3/24.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.029.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.030.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Masuk DHCP Setup, lalu pilih interface Bridge1 yaitu bridge yang sudah kita setup pada step sebelumnya.
<br>

<<<<<<< HEAD
![](images/tugas3/25.png)
<br>

![](images/tugas3/26.png)
<br>

![](images/tugas3/27.png)
<br>

![](images/tugas3/28.png)
<br>

![](images/tugas3/29.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.031.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.032.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.033.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.034.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.035.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Disini kami coba set IP yang akan diberikan mulai dari .200 - .254
<br>

<<<<<<< HEAD
![](images/tugas3/30.png)
<br>

![](images/tugas3/31.png)
<br>

![](images/tugas3/32.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.036.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.037.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.038.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Setup DHCP berhasil ditambahkan
<br>

<<<<<<< HEAD
![](images/tugas3/33.png)
<br>

![](images/tugas3/34.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.039.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.040.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Koneksi sudah tersambung, tetapi belum bisa mengakses internet
<br>

<<<<<<< HEAD
![](images/tugas3/35.png)
<br>

![](images/tugas3/36.png)
<br>

![](images/tugas3/37.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.041.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.042.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.043.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Step terakhir agar bisa tersambung ke akses internet yaitu dengan set Firewall
<br>

<<<<<<< HEAD
![](images/tugas3/38.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.044.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Masuk ke tab submenu NAT
<br>

<<<<<<< HEAD
![](images/tugas3/39.png)
<br>

Tambahkan rule NAT baru untuk Network bridge kita ke semua destination network
<br>

![](images/tugas3/40.png)
<br>

Lalu masuk ke tab submenu Action dan ubah action menjadi masquerade.
<br>

![](images/tugas3/41.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.045.png)

Tambahkan rule NAT baru untuk Network bridge kita ke semua destination network![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.046.png)

Lalu masuk ke tab submenu Action dan ubah action menjadi masquerade.![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.047.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Berhasil ditambahkan rule NAT.
<br>

<<<<<<< HEAD
![](images/tugas3/42.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.048.png)


>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Kita coba kembali tes apakah sudah terkoneksi ke akses internet
<br>

<<<<<<< HEAD
![](images/tugas3/43.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.049.png)


>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

Berhasil terkoneksi
<br>

<<<<<<< HEAD
![](images/tugas3/44.png)
<br>
=======
![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.050.png)
>>>>>>> 514780db24742ef16a58804b06e09fd7ffdd7fb5

![](images/tugas3/45.png)
<br>

SELESAI

```

```
