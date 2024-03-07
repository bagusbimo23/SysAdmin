<div align="center">
  <h1 style="text-align: center;font-weight: bold">LAPORAN WORKSHOP ADMINISTRASI JARINGAN<br>Tugas 3</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : <br>Kelompok 3</h3>
  <p style="text-align: center;">
    <strong>Mahendra Khibrah Rabbani Sayyid (3122500013)</strong><br>
    <strong>Akmal Zidani Fikri (3122500019)</strong><br>
    <strong>Bagus Bimo Prakoso (3122500028)</strong>
  </p>

<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
<hr>
<hr>
</div>

**Gdebi**

Intstall gdebi menggunakan apt

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.001.png)

Pilih package .deb lalu pilih untuk install melalui gdebi

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.002.png)











Pada tampilan gdebi klik untuk install package

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.003.png)

Sebelum install, kita akan dimintai untuk memasukkan password user

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.004.png)

Berikut adalah proses instalasi dari .deb file![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.005.png)

Kita bisa menghapus package dengan menekan menu dari remove package

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.006.png)







**DPKG**

Install deb file menggunakan dpkg di cli

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.007.png)

Jika terdapat error maka install satu per satu dependency yang diperlukan menggunakan apt

Untuk menghapus package deb bisa menggunakan command

Dpkg –purge nama\_package

Buka WinBox dan pastikan terhubung dengan LAN Mikrotik. 
Menghubungkan MAC Address Mikrotik dengan mode Legacy.![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.008.png)

Set IP Address baru untuk ethernet 1 dengan masuk ke menu IP àAddress.

![ref1]

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.010.png)

IP Baru berhasil ditambahkan 

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.011.png)



Set Bridge

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.012.png)

Buat bridge baru

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.013.png)

Bridge berhasil ditambahkan.

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.014.png)Pindah ke tab submnu ports untuk menambahkan port secara manual,
untuk port ether2,3,4,5 agar menjadi satu switch bridge.

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.015.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.016.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.017.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.018.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.019.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.020.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.021.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.022.png)

Setelah set bridge dan menyatukan port ether2,3,4,5 menjadi satu switch, 
selanjutnya tambahkan ip address untuk port yang jadi satu tadi.

![ref1]

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.023.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.024.png)

Setelah itu set route, agar bisa tersambung ke gateway

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.025.png)

Ini default setelah set IP pada step sebelumnya

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.026.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.027.png)

Route ke gateway berhasil ditambahkan

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.028.png)

Selanjutnya set DHCP, agar setiap device yang connect mendapatkan IP secara otomatis atau dinamis.

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.029.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.030.png)

Masuk DHCP Setup, lalu pilih interface Bridge1 yaitu bridge yang sudah kita setup pada step sebelumnya.

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.031.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.032.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.033.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.034.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.035.png)

Disini kami coba set IP yang akan diberikan mulai dari .200 - .254

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.036.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.037.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.038.png)

Setup DHCP berhasil ditambahkan

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.039.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.040.png)

Koneksi sudah tersambung, tetapi belum bisa mengakses internet

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.041.png)![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.042.png)

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.043.png)

Step terakhir agar bisa tersambung ke akses internet yaitu dengan set Firewall

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.044.png)

Masuk ke tab submenu NAT

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.045.png)

Tambahkan rule NAT baru untuk Network bridge kita ke semua destination network![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.046.png)

Lalu masuk ke tab submenu Action dan ubah action menjadi masquerade.![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.047.png)

Berhasil ditambahkan rule NAT.

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.048.png)



Kita coba kembali tes apakah sudah terkoneksi ke akses internet

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.049.png)



Berhasil terkoneksi

![](images/tugas3/Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.050.png)

` `SELESAI

[ref1]: Aspose.Words.3d8914c0-3b43-4fc2-85cb-8c852fe7c974.009.png
