<div align="center">
  <h1 style="text-align: center;font-weight: bold">LAPORAN WORKSHOP ADMINISTRASI JARINGAN<br>Tugas 5</h1>
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

# <a name="_y67ou7mqjs8p"></a>**INSTALASI PACKAGE YANG DIPERLUKAN**

Install timesyncd, apache2, dan php

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.001.png)

Install mariadb, postfix, dan dovecot

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.002.png)

Pilih menu no configuration saat memilih tipe konfigurasi pada postfix

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.003.png)

# <a name="_r8e94kq7i7cp"></a>**SET DATETIME DENGAN NTP**

Set yang diperlukan, lalu restart dan lihat statusnya

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.004.png)

Untuk mengecek, bisa menggunakan command timedatectl. Akan muncul time saat ini

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.005.png)

# <a name="_6d61spu0472c"></a>**INSTALASI APACHE2**

Konfigurasi apache2

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.006.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.007.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.008.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.009.png)

Setelah melakukan konfigurasi, selanjutnya reload apache dengan systemctl.

Untuk melakukan pengecekan terhadap apache, dapat menggunakan web browser.

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.010.png)

# <a name="_ij37s0wrnls8"></a>**INSTALASI PHP 8.2**

Konfigurasi php

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.011.png)

Konfigurasi php-fpm

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.012.png)![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.013.png)

Buat file info.php di var/www/html

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.014.png)

Cek di web browser mengenai info.php ![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.015.png)

# <a name="_22v8cshurmu0"></a>**INSTALASI DATABASE**

Install melalui root user menggunakan command mysql_secure_installation

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.016.png)

Untuk mengecek apakah berhasil di install, gunakan command mysql

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.017.png)

# <a name="_sf93vzbe7cjv"></a>**INSTALASI SMTP SERVER**

Konfigutasi pada file postfix/main.cf

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.018.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.019.png)

Beri kode ini agar untuk mengaktifkan anti spam

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.020.png)

# <a name="_ssntt65w16u6"></a>**INSTALASI DOVECOT**

Berikut ini adalah instalasi dari dovecot

# ![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.021.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.022.png)![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.023.png)![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.024.png)

<a name="_5z3ymrsyk2ab"></a>Untuk mengeceknya bisa menggunakan netstat untuk melihat semua service, dan telnet untuk mengecek layanan postfix

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.025.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.026.png)

# <a name="_rmg1fmsn4x2q"></a>**INSTALASI PHPMYADMIN**

Install phpmyadmin menggunakan apt

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.027.png)

Konfigurasi di webserver apache2

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.028.png)

Konfigurasi pada apache2.conf agar bisa akses /phpmyadmin

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.029.png)

Buat user dengan password

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.030.png)

Testing pada web browser

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.031.png)

# <a name="_6dinjbm70fto"></a>**EMAIL KLIEN MENGGUNAKAN THUNDERBIRD**

Buat 2 user bernama mahen dan akmal

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.032.png)

Coba login pada thunderbird

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.033.png)

Jika berhasil login maka seperti ini tampilannya.

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.034.png)

# <a name="_ku218sssnujs"></a>**INSTALASI ROUNDCUBE**

Untuk install roundcube, gunakan apt install roundcube roundcube-mysql

Lalu ikuti proses instalasinya

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.035.png)

Setelah instalasi ubah password roundcube yang ada pada database

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.036.png)

Ubah juga pada konfigurasi database roundcube

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.037.png)

Sesuaikan konfigurasi dengan alamat ip server kita

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.038.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.039.png)

Berikut adalah tampilan roundcube setelah berhasil di konfigurasi

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.040.png)

![](Aspose.Words.052f5db2-20ac-4ee2-85fd-d173cdc849e2.041.png)
