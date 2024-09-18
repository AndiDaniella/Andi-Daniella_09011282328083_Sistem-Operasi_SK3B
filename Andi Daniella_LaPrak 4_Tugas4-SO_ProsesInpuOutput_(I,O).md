NAMA : ANDI DANIELLA MEZAURI <BR/>
NIM : 09011282328083 <BR/>
KELAS : SK3B <BR/>
MK   : Sistem Operasi  <BR/>
(TUGAS 4)  <BR/>

# LAPORAN PRAKTIKUM 4_Modul PROSES INPUT OUTPUT I/O

# TUGAS

## 1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru.
<img src = "https://github.com/user-attachments/assets/6bb56c55-2d24-446d-b8e1-c097a75a5052" width = 500/>
<img src = "https://github.com/user-attachments/assets/dfc9b0e5-be6b-44d7-8758-46f02561b2d7" width = 500/> <BR/>

## 2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya.
<img src = "https://github.com/user-attachments/assets/fe58408a-3f8d-4f53-8dcd-c96d07a91402" width = 500/> <BR/>

## 3. Urutkan file baru dengan cara membelokkan standard input.
<img src = "https://github.com/user-attachments/assets/90b64e7a-2839-4b92-b07b-cb9d9ee95791" width = 500/> <BR/>

## 4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.
<img src = "https://github.com/user-attachments/assets/66094f6c-824c-4b3d-b1b6-f37075cf0781" width = 500/>
<img src = "https://github.com/user-attachments/assets/9a38b6f6-5f3d-4821-8a89-6958563adf13" width = 500/>  <BR/>

## 5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.
<img src = "https://github.com/user-attachments/assets/34280945-b9b8-4255-8e78-b483a5ca7319" width = 500/>
<img src = "https://github.com/user-attachments/assets/c336f28f-99ff-4725-b652-ebee68ac6c16" width = 500/>
<img src = "https://github.com/user-attachments/assets/8864f58b-d3fa-443d-aebe-077f3b2ecdae" width = 500/> <BR/>

## 6. Urutkan kalimat berikut : 
Jakarta <br/>
Bandung <br/>
Surabaya <br/>
Padang <br/>
Palembang <br/>
Lampung <br/>
Dengan menggunakan notasi here document (<@@@ …@@@)<br/>
<img src = "https://github.com/user-attachments/assets/67d9f3b3-c406-4415-806f-cdbb5b1004ef" width = 500/> <BR/>

## 7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.
<img src = "https://github.com/user-attachments/assets/67d9f3b3-c406-4415-806f-cdbb5b1004ef" width = 500/> <BR/>
**Penjelasan:** <BR/>
- wc baru.urut menghitung jumlah baris, kata, dan karakter pada file baru.urut. <BR/>
- tee -a file_baru.txt menampilkan hasil di layar sekaligus menambahkan hasil tersebut ke file file_baru.txt tanpa menimpa isinya. <BR/>
Jadi, perintah ini memastikan untuk bisa melihat hasilnya di layar dan juga menambahkannya ke dalam file. <BR/>

## 8. Gunakan perintah di bawah ini dan perhatikan hasilnya.
- $ cat /etc/passwd | sort | pr –n | grep tty03 <br/>
- $ find /etc –print | head <br/>
- $ head /etc/passwd | tail –5 | sort <br/>
**HASIL :** <br/>
<img src = "https://github.com/user-attachments/assets/280dad70-84f3-46df-b4c2-5e296fa5bfc7" width = 500/> <BR/>
Ouput : Perintah pertama mencari entri dengan "tty03", perintah kedua menampilkan 10 hasil pertama dari /etc, dan perintah ketiga menampilkan 5 baris terakhir dari 10 baris pertama file /etc/passwd setelah diurutkan. <BR/>

## 9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.
<img src = "https://github.com/user-attachments/assets/cebf68cf-5757-40b0-ab99-cff78568cd07" width = 500/> <BR/>
Ini adalah perintah berlapis yang menampilkan siapa yang login, mengurutkan daftar, dan memotong hasilnya, tetapi output terakhir tergantung pada sistem dan pengguna yang sedang login. <BR/>


