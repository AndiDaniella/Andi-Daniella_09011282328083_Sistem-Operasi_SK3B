<h1> LAPORAN PRAKTIKUM 1_INSTALASI UBUNTU 24.04 LTS_SISTEM OPERASI </h1>
<h2> PENDAHULUAN </h2>
<h3> LATAR BELAKANG </h3>
<p> Mata kuliah Sistem Operasi adalah salah satu komponen penting dalam pendidikan teknologi informasi, yang memberikan pemahaman mendalam tentang cara kerja, pengelolaan, dan pengaturan sistem operasi. Dalam konteks ini, penguasaan terhadap instalasi dan konfigurasi sistem operasi Linux, khususnya Ubuntu 24.04 LTS, menjadi esensial. Ubuntu, sebagai salah satu distribusi Linux yang paling populer, sering digunakan karena kestabilannya, kemudahan penggunaannya, dan dukungan komunitas yang luas. </p>
<p> Untuk mendukung pembelajaran yang efektif, praktikum ini dirancang untuk memberikan pengalaman langsung dalam instalasi Ubuntu 24.04 LTS menggunakan aplikasi virtualisasi VirtualBox. VirtualBox dipilih karena kemampuannya untuk menjalankan beberapa sistem operasi secara bersamaan pada satu perangkat keras tanpa mengganggu sistem operasi utama, sehingga menjadi alat yang ideal untuk keperluan pembelajaran dan eksperimen. </p>
<p> Selama praktikum, peserta akan mempelajari proses instalasi Ubuntu dalam lingkungan virtual, mulai dari persiapan mesin virtual hingga konfigurasi akhir sistem operasi. Praktikum ini juga mencakup pemahaman tentang berbagai jenis sistem file yang digunakan selama instalasi, seperti ext4, ext3, swap, ntfs, fat32, dan btrfs. Masing-masing sistem file ini memiliki karakteristik dan fungsi spesifik yang penting untuk diketahui, terutama dalam hal performa, keamanan, dan kompatibilitas. </p>
<p> Sebagai bagian dari tugas akhir dalam praktikum ini, peserta diminta untuk melakukan analisis terhadap gambar yang menunjukkan proses pemilihan opsi “/” pada tahap Mount saat instalasi. Langkah ini krusial dalam menentukan struktur direktori root, yang merupakan fondasi dari sistem operasi. Selain itu, peserta juga diminta untuk memberikan penjelasan detail mengenai sistem file yang telah disebutkan sebelumnya, termasuk kelebihan, kekurangan, serta aplikasi yang tepat dari masing-masing sistem file tersebut. </p>
<p> Melalui praktikum ini, diharapkan peserta mampu menguasai teknik instalasi dan konfigurasi Ubuntu 24.04 LTS menggunakan VirtualBox, serta memiliki pemahaman yang kuat tentang manajemen partisi dan sistem file dalam konteks sistem operasi modern. </p>
<h3> TUJUAN LAPORAN </h3>
Berikut tujuan pembuatan laporan praktikum ini dibuat agar : <br/>
1. Mengetahui prosedur instalasi pada sistem operasi linux <br/>
2. Mampu menjalankan instalasi melalui Graphic User Interface (GUI) maupun Command Line Linux <br/>
3. Mampu menganalisis proses instalasi <br/>
<h3> ALAT DAN BAHAN </h3>
1. Laptop Pribadi <br/>
2. Modul/PPT tutorial dan tugas <br/>
3. Aplikasi Virtualisasi, Virtual box <br/>
4. Ubuntu 24.04 LTS <br/>
<h3> DASAR TEORI </h3>
<p> Sistem operasi mengelola perangkat keras dan perangkat lunak komputer, dengan Linux, khususnya Ubuntu, sering digunakan karena stabilitasnya. VirtualBox memungkinkan menjalankan beberapa sistem operasi di satu perangkat tanpa mengganggu sistem utama. </p>
<p> Sistem file seperti ext4, swap, ntfs, fat32, dan btrfs memiliki peran penting dalam manajemen data. Ext4 adalah sistem file default Ubuntu, swap digunakan sebagai memori tambahan, sementara ntfs dan fat32 lebih umum di Windows. Btrfs menawarkan fitur lanjutan seperti snapshotting. </p>
<p> Pemilihan direktori root (“/”) pada opsi Mount saat instalasi menentukan struktur dasar dan akses utama sistem operasi terhadap file dan direktori.</p>

<h2> PEMBAHASAN </h2>
<h3> Langkah-langkah Instalasi Ubuntu </h3>

1. Untuk mengunduh file ISO distribusi Ubuntu 24.04 LTS dari situs resmi, kunjungi situs web Ubuntu, lalu masuk ke bagian unduhan dan pilih versi yang diinginkan. Cari tombol "Unduh," dan setelah mengkliknya, file ISO akan mulai diunduh ke perangkat Anda. Pastikan untuk memverifikasi integritas file menggunakan checksum yang disediakan agar proses instalasi berjalan lancar. <br/>

2. Lalu, instal juga Oracle VM VirtualBox dari situs web resminya <br/>

3. Instal VirtualBox <br/>
* Buka file instalasi VirtualBox yang telah diunduh. <br/>
* Ikuti panduan instalasi sampai selesai.<br/>
* Setelah instalasi selesai, buka VirtualBox.<br/>

4. Buat Mesin Virtual Baru <br/>
* Klik tombol "New" atau "Baru" di VirtualBox.<br/>
* Beri nama mesin virtual (misalnya, "Ubuntu 24.04 LTS").<br/>
* Pilih tipe "Linux" dan versi "Ubuntu (64-bit)".<br/>
* Klik "Next" atau "Lanjutkan".<br/>

5. Alokasikan Memori (RAM) <br/>
* Tentukan jumlah RAM yang akan dialokasikan untuk mesin virtual.<br/>
* Disarankan setidaknya 2 GB (2048 MB) atau lebih, tergantung pada kapasitas komputer Anda.<br/>
* Klik "Next".<br/>

6. Buat Hard Disk Virtual <br/>
* Pilih opsi "Create a virtual hard disk now" atau "Buat hard disk virtual sekarang".<br/>
* Klik "Create" atau "Buat".<br/>
* Pilih format file hard disk (disarankan VDI).<br/>
* Pilih opsi "Dynamically allocated" agar ukuran disk bertambah seiring kebutuhan.<br/>
* Tentukan ukuran disk (misalnya, 20 GB atau lebih).<br/>
* Klik "Create".<br/>

7. Konfigurasi Mesin Virtual <br/>
* Setelah mesin virtual dibuat, pilih mesin tersebut dan klik "Settings" atau "Pengaturan".<br/>
* Masuk ke tab "Storage" atau "Penyimpanan".<br/>
* Klik ikon "Empty" atau "Kosong" di bawah pengontrol "IDE".<br/>
* Klik ikon CD di sebelah kanan dan pilih "Choose a disk file" atau "Pilih file disk".<br/>
* Pilih file ISO Ubuntu yang telah Anda unduh.<br/>
* Klik "OK" untuk menyimpan pengaturan.<br/>

8. Mulai Mesin Virtual <br/>
* Pilih mesin virtual Ubuntu dan klik "Start" atau "Mulai".<br/>
* Mesin virtual akan memuat ISO Ubuntu dan memulai proses instalasi.<br/>

9. Instal Ubuntu di VirtualBox <br/>
* Ikuti panduan instalasi Ubuntu di layar, pilih bahasa, zona waktu, dan partisi disk sesuai kebutuhan Anda. <br/>
<img src="https://github.com/user-attachments/assets/90ea7c2c-dc17-41ce-9cf5-cb9974905171" width=500/>
<img src="https://github.com/user-attachments/assets/afeb54b0-bfea-4731-a561-02b9a2c124bb" width=500/>
<img src="https://github.com/user-attachments/assets/f4c196cc-e973-4709-8660-2d93f3f2e757" width=500/>
<img src="https://github.com/user-attachments/assets/5485b138-270d-42eb-b777-89826f50ef01" width=500/>
<img src="https://github.com/user-attachments/assets/ffebbb9d-a615-49f5-adc2-ddcd349d946a" width=500/>
<img src="https://github.com/user-attachments/assets/7b4c3b1b-4977-410c-a777-39777ed63eee" width=500/>
<img src="https://github.com/user-attachments/assets/696338a3-9765-464b-9ce2-a0eb179e87d7" width=500/>
<img src="https://github.com/user-attachments/assets/733c591e-e154-4592-ba4f-6e62801e5162" width=500/>
<img src="https://github.com/user-attachments/assets/f4aadc39-fe70-4e52-9f80-632a7714e1ee" width=500/>
<img src="https://github.com/user-attachments/assets/2f89f345-8a7b-4145-b222-6e5ddd12a2dc" width=500/>
<img src="https://github.com/user-attachments/assets/b781ae9e-8aa5-4cbf-be36-f21823636919" width=500/>
<img src="https://github.com/user-attachments/assets/72e60de8-20b8-4939-8201-dba76c6a9b74" width=500/>
<img src="https://github.com/user-attachments/assets/492e6fb5-e272-43da-bcdb-0efc67827a99" width=500/>
<img src="https://github.com/user-attachments/assets/99cd2f11-fe66-4c9b-9494-8436abafa326" width=500/>

* Setelah instalasi selesai, restart mesin virtual. <br/>
9. Lepaskan ISO dan Reboot <br/>
* Setelah instalasi selesai, buka pengaturan mesin virtual dan lepaskan ISO dari drive virtual. <br/>
* Reboot mesin virtual untuk memulai Ubuntu dari hard disk virtual yang baru saja Anda buat. <br/>
10. Mulai Menggunakan Ubuntu <br/>
* Ubuntu akan boot, dan Anda bisa mulai menggunakannya di dalam VirtualBox. <br/>

<h3> TUGAS </h3>
<h4> 1. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ? </h4>
<p> Memilih “/” sebagai mount point saat instalasi Linux sangat penting karena “/” adalah direktori root, yang merupakan lokasi utama di mana seluruh sistem operasi dan file penting lainnya diinstal. Dengan menetapkannya sebagai mount point, Anda memastikan bahwa semua komponen sistem terstruktur dengan benar di bawah direktori ini, menjaga stabilitas, keamanan, dan keteraturan sistem file Linux. </p>

<h4> 2. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !</h4>
<p> Berikut adalah penjelasan singkat tentang masing-masing sistem file:

1. **ext4**: **Extended Filesystem 4** adalah sistem file yang umum digunakan di Linux, menawarkan peningkatan kinerja, keandalan, dan ukuran file serta partisi yang lebih besar dibandingkan dengan pendahulunya, ext3. Mendukung fitur seperti journaling dan defragmentasi otomatis.

2. **ext3**: **Extended Filesystem 3** adalah sistem file Linux yang mendukung journaling, yang membantu melindungi data saat terjadi kerusakan. Meskipun stabil dan andal, ext3 kurang efisien dibandingkan ext4 dalam hal kecepatan dan manajemen ruang disk.

3. **swap**: Swap bukan sistem file, tetapi ruang pada disk yang digunakan sebagai memori virtual saat RAM fisik penuh. Sistem menggunakan swap untuk memperluas kapasitas memori, meskipun aksesnya lebih lambat dibandingkan RAM.

4. **ntfs**: **New Technology File System** adalah sistem file yang dikembangkan oleh Microsoft, digunakan terutama oleh Windows. Mendukung fitur seperti file permission, encryption, dan journaling. Cocok untuk penyimpanan besar dan partisi Windows.

5. **fat32**: **File Allocation Table 32** adalah sistem file yang lebih tua dan kompatibel dengan banyak sistem operasi, termasuk Windows, Linux, dan macOS. Namun, memiliki keterbatasan seperti ukuran file maksimal 4GB dan partisi maksimal 2TB.

6. **btrfs**: **B-tree Filesystem** adalah sistem file modern untuk Linux yang mendukung fitur-fitur canggih seperti snapshot, pooling, dan integritas data. Btrfs dirancang untuk menjadi sistem file generasi berikutnya dengan fokus pada skalabilitas dan kinerja.</p>


<h2> KESIMPULAN </h2>
<p> Praktikum ini memberikan pengalaman langsung dalam menginstal dan mengkonfigurasi Ubuntu 24.04 LTS menggunakan VirtualBox, sebuah alat virtualisasi yang memungkinkan menjalankan beberapa sistem operasi pada satu perangkat keras tanpa mengganggu sistem utama. Dengan mengikuti prosedur instalasi, baik melalui antarmuka grafis (GUI) maupun Command Line, peserta dapat memahami langkah-langkah teknis dan praktis yang terlibat dalam proses instalasi sistem operasi Linux. </p>
<p> Selain itu, praktikum ini juga mengedepankan pemahaman mendalam mengenai berbagai sistem file seperti ext4, ext3, swap, ntfs, fat32, dan btrfs, serta pentingnya pemilihan mount point, khususnya direktori root ("/") dalam struktur sistem file. Analisis terhadap proses ini membantu peserta memahami bagaimana sistem file dan pengaturan partisi mempengaruhi kinerja, keamanan, dan kompatibilitas sistem operasi. Melalui praktikum ini, diharapkan peserta dapat menguasai teknik instalasi dan konfigurasi serta memperoleh keterampilan yang relevan dalam manajemen sistem operasi modern.</p>
