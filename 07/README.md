Modul 7
Cloud Computing

Tugas 0:
1. Carilah berbagai contoh vendor/komunitas SaaS, PaaS, dan IaaS masing-masing 1
saja.
Jawab:
| Jenis | Vendor              | Layanan                             |
| ----- | ------------------- | ----------------------------------- |
| SaaS  | Google              | Google Docs, Gmail, Google Drive    |
| PaaS  | Heroku              | Platform deploy aplikasi web        |
| IaaS  | Amazon Web Services | Server virtual, storage, networking |

2. Uraikan apa yang menjadi service dari berbagai vendor untuk berbagai kategori
XaaS tersebut.
Jawab:
SaaS
Pengguna langsung memakai aplikasi melalui internet tanpa mengelola server atau sistem operasi.
Contoh: Gmail dan Google Docs.

PaaS
Provider menyediakan platform untuk membuat dan menjalankan aplikasi tanpa mengelola infrastruktur.
Contoh: Heroku menyediakan runtime, database, dan deployment otomatis.

IaaS
Provider menyediakan infrastruktur virtual seperti VM, storage, dan jaringan.
Pengguna mengelola OS dan aplikasinya sendiri.

3. Jelaskan secara umum arsitektur dari XaaS tersebut dalam bentuk visualisasi
gambar.
Jawab:
SaaS
User
  |
Internet
  |
Aplikasi Cloud
  |
Server Provider

PaaS
Developer
   |
Platform Cloud
   |
Runtime + Database + OS
   |
Infrastructure

IaaS
User
  |
Virtual Machine
  |
Virtualization Layer
  |
Physical Server

Asumsikan direktori kerja ada di $HOME/src.
<img width="948" height="242" alt="image" src="https://github.com/user-attachments/assets/74b8e426-846f-471e-b583-fc04d6445631" />

Source code berada di examples/tutorial. Pada titik ini, silakan meng-copy direktori
tutorial tersebut ke direktori tertentu:
<img width="911" height="191" alt="image" src="https://github.com/user-attachments/assets/8db2d696-7181-453b-8ca7-2f7a770a2d40" />

masuk ke direktori baru tersebut:
<img width="607" height="52" alt="image" src="https://github.com/user-attachments/assets/3944d8f8-c379-4cb4-996b-6a7a665784a0" />

1. Membuat env Python 3.14.4
   <img width="690" height="258" alt="image" src="https://github.com/user-attachments/assets/4e5f1a23-e748-42cc-83cf-da23b7f006be" />
2. Install Paket yang Diperlukan
   <img width="858" height="329" alt="image" src="https://github.com/user-attachments/assets/3877f98e-5055-461e-874d-99ad5ff3a7d1" />
   Jalankan aplikasi tersebut setelah inisialisasi database:
   <img width="940" height="236" alt="image" src="https://github.com/user-attachments/assets/1e25be37-fb01-4e3c-935c-c25cfcc17dc4" />
   Kita bisa melihat aplikasi berjalan di browser:
   <img width="955" height="229" alt="image" src="https://github.com/user-attachments/assets/3e916c62-f064-4409-a8f1-ce729acd0f01" />
3. Buat Aplikasi Menjadi CA - Docker
   Buat image dengan perintah (jangan lupa ada titik di paling belakang):
   <img width="940" height="934" alt="image" src="https://github.com/user-attachments/assets/044150e4-778d-4234-85ae-7296e079e829" />
   Image telah berhasil dibuat:
   <img width="963" height="141" alt="image" src="https://github.com/user-attachments/assets/fea59c37-e46c-40bb-9357-eb2558c16e88" />
4.  Menjalankan Image
   <img width="936" height="251" alt="image" src="https://github.com/user-attachments/assets/19921359-a27c-4081-9918-f4e219151dfb" />
    Buka di browser:
   <img width="955" height="208" alt="image" src="https://github.com/user-attachments/assets/865edafc-0ba1-4a3b-aa6e-856c668b6da0" />
5. Buat Aplikasi Menjadi CA - Podman
   <img width="956" height="966" alt="image" src="https://github.com/user-attachments/assets/7db695f5-acc5-4463-986c-cdbfd38c7bf5" />
   <img width="953" height="969" alt="image" src="https://github.com/user-attachments/assets/af50e90a-4e1d-4d2c-b251-8498f68654ee" />

   Image telah berhasil dibuat:
   <img width="954" height="134" alt="image" src="https://github.com/user-attachments/assets/53b42d0a-87ad-4161-abe5-55b6bacf5310" />
   Jalankan dengan memetakan port 5000 pada aplikasi di container ke port 5001 di localhost:
   <img width="945" height="249" alt="image" src="https://github.com/user-attachments/assets/5f0c345b-e0c9-448f-b31a-092856b373b5" />
   <img width="956" height="206" alt="image" src="https://github.com/user-attachments/assets/1ef00868-9a69-4764-b796-9670bd3acd65" />
