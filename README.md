![image](https://github.com/user-attachments/assets/ba82ece3-fbd9-42cd-9e68-51567bdd9d2e)# Pratikum Jarkom-Modul-1-IT22-2024

**KELOMPOK IT22**
| Nama | NRP |
|---------------------------|------------|
|Muhamad Arrayyan | 5027231014 |
|Fadlillah Cantika Sari Hermawan | 5027231042 |

## Pengantar
Laporan resmi ini dibuat terkait dengan praktikum modul 1 jaringan komputer yang telah dilaksanakan pada tanggal 18 September 2024 hingga tanggal 19 September 2024. Praktikum modul 1 terdiri dari 20 soal yang dikerjakan dan diselesaikan dalam bentuk CTF.

## Write Up

### `1. Advance Sanity Check`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze - TCP Stream
4. Pada stream 3 berisi (username)
5. Pada stream 4 berisi (string)
6. Peraturan Soal Shift jarkom, di decode ke teks menggunakan base64
7. String (penword)
8. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/075a29f2-f237-46a4-9a65-833924ce41b7">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/1d73b78b-6b21-4f8a-93ee-041ec8660652">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/daaab6f8-b3f7-452c-840a-1a1016e101f3">

</details>


### `2. Pegawai Negeri Sebelah`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Terus follow TCP stream
5. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/bae7616b-b46e-454e-a29e-95e269c5a973">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/200ce4f0-ef13-45c4-88ae-fa7eec3736c2">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/6f1e8c9b-e0a9-4b9f-b118-c0db4da22009">

</details>

### `3. EZ`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Terus follow TCP stream
5. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/f1803e60-bd39-4122-a122-59e75c59dc3e">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/b9448c48-4433-463a-ae15-27381127b93d">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/6ce53b60-8caf-4028-bfb1-d658150a71c2">

</details>

### `4. Rizzset`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Bisa di filter di stream dengan dns
5. Terus pantau yang memiliki IP DNS
6. Terus follow TCP stream
7. Begitu juga dengan IP dan dns query nya
8. Lalu git clone jarm untuk mendapatkan kode jarm
9. lalu bisa denga command `python jarm.py its.ac.id`
10. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/9e386d36-9cbb-4e34-b24c-56ce2c0c898a">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/9a8519c3-0006-4827-b3fd-4961cb9e46dc">

Jarm
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/e6a47b04-26f3-44f0-b010-22c962f8541d">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/5fec6c40-0d17-4ab8-9568-dfa98df87b31">

</details>

### `5. FTP Login`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Terus follow TCP stream
5. Lalu filter di stream sampe menemukan user benar
6. Begitu juga dengan password nya
7. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/3510d81b-6a83-427a-ae8e-bbd161fba5e8">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/3894f5c5-562f-41e2-99a7-2977edfd20ee">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/6f85bcab-2e88-408a-aee8-cdbf865667ad">

</details>

### `6. Surprise`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Bisa di filter di stream dengan mencari yang sesuai diminta pada nc terminal
5. Terus cari service dan saya menemukan `vsFTPd 3.0.3`
6. Lalu cari didalamnya yang mengandung sebuah file `g0tcha.cpp`
7. Decode sebuah kode agar menjadi sebuah pesan
8. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/669e4661-1bf8-4a0b-86d8-d170b4683fbb">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/f7c56585-f798-4173-9217-4764a8f7bcd0">
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/ad5ca73a-0fde-4647-a3c6-28679d843a81">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/0f74d503-8ff4-4a64-b5d5-ea61d1f1315b">

</details>

### `7. Illegal Breakthrough`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Bisa di filter di stream dengan dns
5. Terus cari IP korban 
6. Terus cari juga port 
7. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/317e0ed6-eeda-4125-a841-4b1a60e4ebe2">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/c15fd7a0-5c81-4e8b-b72f-b5ee3f6f5508">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/c6e438fc-fe02-441e-95b5-0bb74c3e0201">

</details>

### `8. Packets Barrage`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Bisa di filter di stream dengan dns
5. Terus cari IP attacker
6. Terus cari juga port
7. Lalu Export file to HTTP
8. Setelah itu cari file pesan disini saya menemuka `Albatros.txt`
9. Kemudian buka filenya dan lihat isinya lalu masukan ke terminal
10. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/7becfeb4-0bbc-4495-8658-712fd537b618">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/c15fd7a0-5c81-4e8b-b72f-b5ee3f6f5508">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/3c125f26-27c9-4aff-96f4-1b19dfe95527">

</details>

### `9. Corporate Breach`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze
4. Terus follow TCP stream
5. Lalu filter di stream sampe menemukan user benar
6. Begitu juga dengan email dan password nya
7. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/007ed4f0-21c2-426d-84a7-ff04531d8070">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/80b64704-0727-4733-89c9-0a51fae63120">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/fffe7ff7-0ead-4e4b-bb2b-ea2a6ec2dc9b">

</details>

### `10. Malicious Code`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. Bisa memilih dibagian atas pada bagian analyze'
4. Setelah itu total semua stream nya ada 222
5. Bisa di filter `http.request.method == "GET"`
6. Terus ada berapa stream untuk GET disini dapat dilihat pada `stream 52`
7. Terus cari endpoint keberapa hacker berhasil login
8. Lalu hacker melakukan bruteforce dan berhasil mendapatkan email dan password pada `stream 54`
9. setelah itu kita kembali ke soal `Corporate Breach` kita menemukan email dan password jarkom pada stream 
10. Ditemukan pada stream 207 yang berisikan email
11. Lalu untuk mengetahui attempt berapa hacker mengetahui email dan password dengan cara `222-207 = 15` setelah itu `222-15-54 = 153`
12. Nah Pada attempt ke stream 153 attacker menemukan email dan password yang benar
13. Setelah itu pada `stream 221` ada pesan dari hacker, akan tetapi kita perlu mendecode kode yang diberikan agar menjadi sebuah teks
14. Setelah dienkripsi kita bisa mengetahui pesannya, dan kita disuruh untuk memberikan jawaban untuk menjawab pertanyaannya
15. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/1e124863-66c5-4fa4-95de-1f8e06b9e365">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/c508da18-cf20-49b5-8a28-4f2d4878acb3">
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/3f28c90c-f840-42f8-87d7-5ef35bce6c6f">
Stream 54
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/b0c8fa9b-741e-4ef7-8b8c-e7e1a187c859">
Stream 207
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/0eb67fd0-257b-4595-88ef-8bd93597e095">
Stream 221
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/0858458c-aab7-4341-97f1-6275e0ff6c42">

NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/d3104820-0af0-4950-a354-ae8d832b95ed">

</details>

### `11. Simnba`
1. Download file package yang sudah disediakan
2. Setelah itu buka package tadi di wireshark
3. service seperti TCP, MDNS, dan ARP, jawaban yang benar adalah pada "SMB"
4. Saya mulai memfilter service untuk tertuju pada SMB
5. Lalu mencari nama pada bagian `User: spooky.domain\..`
6. Sehingga saya menemukan nama user "mmeyers"
7. Save file menggunakan langkah Export Objects > SMB
8. Setelah itu menghitung banyaknya file yang tertampil, tetapi dengan mengesampingkan yang memiliki size 0 bytes, hasilnya adalah 14 
9. Berhasil menemukan flag

<img width="1500" alt="image" src="https://github.com/user-attachments/assets/c08ba289-b0ea-464f-a4bb-a54acc70bc65">

<details>

<summary>Detail Gambar</summary>

Wireshark
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/8754341e-6619-4ab6-8afb-867ce31fb159">
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/fd6ae21a-a4f1-4ba3-9cbb-ab6824e360dd">


NC
<img width="1710" alt="image" src="https://github.com/user-attachments/assets/bf96ba10-d005-41a5-898d-f50c2fc0dc56">


</details>

