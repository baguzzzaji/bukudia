# Mengenal dan Memasang Dia
## Mengenal Dia
Diagram adalah gambar yang merepresentasikan suatu informasi menggunakan teknik visualisasi tertentu. Kita terkadang perlu untuk menuangkan ide atau gagasan dalam bentuk diagram salah satu bentuk diagram ialah *flowchart*, denah lantai, organigram, dan lain-lain.

![Contoh flowchart. Sumber : wikipedia.org](http://upload.wikimedia.org/wikipedia/commons/9/91/LampFlowchart.svg)

![Contoh Organigram. Sumber : wikimedia.org](http://upload.wikimedia.org/wikipedia/commons/c/c2/Academies_of_the_RSC_Organigram.png)

Menggambar diagram seperti contoh di atas akan jauh lebih mudah menggunakan aplikasi komputer. Salah satu aplikasi yang paling banyak dikenal orang untuk menggambar diagram adalah Microsoft Visio. Microsoft Visio dibuat oleh perusahaan Microsoft (perusahaan yang sama yang merilis Windows) sebagai aplikasi penggambar diagram dan vektor. Meskipun satu keluarga dengan Microsoft Office, namun Microsoft Visio dijual secara terpisah. 

![Microsoft Visio. Sumber: microsoft.com](http://www.microsoft.com/presspass/images/features/2008/02-05VisioPro_ITChart.jpg)

Microsoft Visio merupakan aplikasi yang sangat bagus untuk menggambar diagram. Aplikasi ini juga merupakan aplikasi yang penulis pertama kali kenal saat sekolah SMK dulu. Namun sayangnya aplikasi ini tidaklah murah. Seperti halnya produk-produk besutan Microsoft, Visio dibanderol dengan harga yang cukup mahal. Menurut informasi dari situs [amazon.com](http://www.amazon.com/Microsoft-Visio-Standard-2013-Card/dp/B009SPNLUE/ref=sr_1_1?ie=UTF8&qid=1418486689&sr=8-1&keywords=visio) harga lisensi untuk Microsoft Visio lebih dari $100 atau jika dirupiahkan lebih dari Rp. 1.000.000,-. 

![Harga Visio diambil dari situs amazon.com](img/harga-visio.png)

Menggunakan aplikasi bajakan bukanlah pilihan yang bijak karena masih ada alternatif aplikasi penggambar diagram yang tak kalah dari aplikasi berbayar Microsoft Visio, Dia.

Dia merupakan aplikasi penggambar diagram yang fungsinya sama dengan Microsoft Visio yakni menggambar berbagai macam diagram. Diagram yang dapat dibuat pun beragam, mulai dari *flowchart*, digaram *UML*, diagram jaringan komputer, sirkuit elektronika, basis data (erd, cdm, pdm), dan lain-lain. Dia bersifat *free and open source*, artinya Dia tersedia gratis untuk kita pakai serta kode aplikasinya dapat kita lihat secara bebas.

![Tangkapan layar Dia. Sumber : dia-installer.de](http://dia-installer.de/en/images/dia_screenshot.png)

Dia pertama kali dibuat oleh Alexander Larsson, namun karena kesibukannya pengembangan dilanjutkan oleh James Henstridge. James Henstridge juga harus mundur karena mengerjakan proyek yang lain dan digantikan oleh Cryrille Chepelov dan Lars Ræder Clausen.

Saat ini Dia dikembangkan oleh sekelompok orang yaitu: Hans Breuer, Steffen Macke, and Sameer Sahasrabuddhe.

Dia dibuat dengan GTK+ dan berjalan diberbagai sistem operasi.

## Memasang Dia
Dia tersedia bagi berbagai sistem operasi seperti Windows, GNU/Linux, Unix, serta Mac OSX. Situs resmi Dia dapat diakses di halaman [http://dia-installer.de/](http://dia-installer.de/). 

![Tampilan web Dia saat buku ini ditulis](img/tampilan-web.png)

### Memasang Dia di Microsoft Windows
Karena sesuatu hal, VirtualBox saya tidak dapat berjalan sehingga tidak dapat membuat panduan pemasangan di Windows. Namun saya menemukan panduan pemasangan di Windows yang cukup lengkap yang saya temui di alamat http://beginlinux.com/appsm/27-dia/1394-dia-installation-on-windows.

Untuk memasang Dia di Windows, pertama unduh dahulu aplikasi Dia di [http://dia-installer.de/download/index.html](http://dia-installer.de/download/index.html). 

![Unduh Dia](http://beginlinux.com/images/courses/dia/dia_win1.gif)

Simpan berkas pemasangnya.

![Simpan berkas pemasang](http://beginlinux.com/images/courses/dia/dia_win2.gif)

Buka folder tempat menyimpan berkas pemasang. Klik dua kali atau, klik kanan open.

![Klik Dia](http://beginlinux.com/images/courses/dia/dia_win3.gif)

Pilih bahasa yang ingin digunakan.

![Pilih bahasa](http://beginlinux.com/images/courses/dia/dia_win4.gif)

Akan muncul jendela pemasangan Dia. Disini klik Next.

![Jendela pertama Dia](http://beginlinux.com/images/courses/dia/dia_win5.gif)

Selanjutnya klik Next untuk menyetujui perjanjian lisensi (*license agreemnet*).
![Jendela setujui *license agreement*](http://beginlinux.com/images/courses/dia/dia_win6.gif)

Klik Next kembali.
![Pilih komponen](http://beginlinux.com/images/courses/dia/dia_win7.gif)

Disini pilih tempat untuk memasang Dia. Secara otomatis Dia akan dipasang di folder C:\Program Files\Dia. Klik Next. Proses pemasangan akan langsung dimulai
![Pilih tempat pemasangan](http://beginlinux.com/images/courses/dia/dia_win8.gif)

Tunggu proses pemasangan selesai.
![Proses pemasangan](http://beginlinux.com/images/courses/dia/dia_win9.gif)

Setelah selesai klik Finish.
![Finish](http://beginlinux.com/images/courses/dia/dia_win10.gif)
### Memasang Dia di GNU/Linux
Jika pembaca menggunakan GNU/Linux apapun distronya, Dia seharusnya dapat langsung dipasang melalui aplikasi menajemen aplikasi di distro yang pembaca gunakan. 

![Dia di Software manager Fedora](img/dia-fedora.png)
![Dia di Ubuntu Software Center. Sumber : saungfoss.dauntal.com](http://saungfoss.dauntal.com/files/2012/12/dia-ubuntu-software-center.png)

Atau pembaca dapat langsung menggunakan terminal untuk memasang Dia.

#### Debian, Ubuntu, Linux Mint, dan turunan-turunannya
```bash
sudo apt-get install dia
```

#### Red Hat, Cent OS, Fedora, dan turunan-turunannya
```bash
sudo yum install dia
```

### Arch Linux
```bash
sudo pacman -S dia
```

#### Open SUSE
```bash
sudo zypper install dia
```
