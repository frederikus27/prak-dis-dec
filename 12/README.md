Modul 12
Teknologi P2P (Peer-to-Peer)

1.	Koneksi antar nodes
simple_chat.py
<img width="811" height="643" alt="image" src="https://github.com/user-attachments/assets/80dc0273-54c6-4461-90c7-2c90fa0db1a3" />
<img width="808" height="451" alt="image" src="https://github.com/user-attachments/assets/cc2b3667-063e-4b4c-9723-4205d0e016b2" />

Jelaskan bagian dalam program tersebut yang digunakan untuk:

a. Membuka port yang akan menerima dan mengirim pesan

b. Menerima pesan

c. Mengirim pesan

<img width="975" height="313" alt="image" src="https://github.com/user-attachments/assets/e0febf1f-205e-41a8-8c61-4b20d9eff027" />
<img width="975" height="277" alt="image" src="https://github.com/user-attachments/assets/43cfe728-65b2-4ad0-a0b4-d9a0c7a6f1ea" />

2.	DHT (Distributed Hash Table)
dht.py
<img width="907" height="661" alt="image" src="https://github.com/user-attachments/assets/167d4d0b-63d4-4be6-97b7-9ce0bd8a00eb" />
<img width="906" height="584" alt="image" src="https://github.com/user-attachments/assets/aad937cb-5867-4db2-81f7-dc41e54fb85d" />

Tugas:

1.	Jalankan program tersebut.
   <img width="975" height="404" alt="image" src="https://github.com/user-attachments/assets/d650f32c-b01a-4a49-b3b4-13f8579a8641" />

2. Jelaskan dengan singkat, apa yang dilakukan oleh program tersebut.
   
    Program mensimulasikan DHT
   
    Setiap file mempunyai hash.
   
    Hash digunakan untuk menentukan node penyimpan data.
   
    Ketika data dicari, sistem mencari node yang bertanggung jawab terhadap hash tersebut
   
3.  Dari program tersebut, jelaskan bagaimana DHT bisa digunakan untuk proses pencarian data yang berada pada node lainnya. Buat algoritmanya.
   
    Mulai
    
    Buat node
    
    Hitung hash node
    
    Simpan node ke ring
    
    Input nama file
    
    Hitung hash file
    
    Cari node terdekat
    
    Simpan data
    
    Saat pencarian:
    
        hitung hash file
    
        cari node terdekat
    
        tampilkan data
    
    Selesai

3.  Torrent
   read_torrent.py
   <img width="970" height="815" alt="image" src="https://github.com/user-attachments/assets/bfa777b0-4617-4711-a5d9-4608e459b585" />

   
  1.	Jalankan program tersebut.
  <img width="975" height="299" alt="image" src="https://github.com/user-attachments/assets/dc4d7b08-b4a8-46ef-846f-de923bab0298" />


  2.	Jelaskan mengapa program tersebut memberi output seperti saat dijalankan.
     
      Output muncul karena program melakukan:
      Membaca file torrent.
      
      Decode data torrent.
      
      Mengambil metadata.
      
      Menghitung info hash.
      
      Menghitung jumlah pieces.
      
      Menampilkan hasil.




