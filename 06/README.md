Modul 6
Distributed File System - HDFS

1. Unduh Apache Hadoop
   <img width="393" height="129" alt="image" src="https://github.com/user-attachments/assets/ff023119-9687-4d11-a4a3-54857036ee75" />

2. Instalasi Apache Hadoop
   <img width="862" height="905" alt="image" src="https://github.com/user-attachments/assets/0fb8ec32-00ee-4255-b28a-ca70bb1aa6d0" />

3. Instalasi pdsh
   <img width="631" height="476" alt="image" src="https://github.com/user-attachments/assets/1dc9aa67-78bf-473c-b181-26e9608d7c9e" />

  Atur supaya ssh ke localhost tidak perlu login
   <img width="931" height="819" alt="image" src="https://github.com/user-attachments/assets/a31893e0-aa25-4894-9714-0dcdac61f265" />

4. Konfigurasi Apache Hadoop
   $HADOOP_HOME/etc/hadoop/hdfs-site.xml
    <img width="845" height="490" alt="image" src="https://github.com/user-attachments/assets/c1dac370-443d-48ef-bd35-9d71c45e84a7" />
    
   $HADOOP_HOME/etc/hadoop/core-site.xml
    <img width="917" height="664" alt="image" src="https://github.com/user-attachments/assets/b0c97f35-27bf-4882-8cda-d455c39d9762" />

   $HADOOP_HOME/etc/hadoop/mapred-site.xml
    <img width="958" height="541" alt="image" src="https://github.com/user-attachments/assets/c4ff1a49-e973-4900-8cac-aecc3386fdfa" />

   $HADOOP_HOME/etc/hadoop/yarn-site.xml
   <img width="955" height="502" alt="image" src="https://github.com/user-attachments/assets/bf7ded51-4a48-493b-af76-97c6b730e157" />

5. Format NameNode
   <img width="1889" height="868" alt="image" src="https://github.com/user-attachments/assets/18153010-6f40-44b7-b256-f41913480af0" />

6. Atur konfigurasi JAVA_HOME
   <img width="935" height="949" alt="image" src="https://github.com/user-attachments/assets/999a94fc-5f7d-4139-86ae-d14ca22fbaa0" />

7. Jalankan daemon untuk HDFS
   <img width="963" height="142" alt="image" src="https://github.com/user-attachments/assets/61de935f-3370-4369-a7de-b8bf2768ed7c" />

   Pemantauan bisa dilakukan menggunakan Web:
   <img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/4c00e4f5-9b00-470d-8ea6-2627443c34d7" />

Tugas:
1. Buat direktori /user/<nama-user>/datasets di HDFS anda
   <img width="1212" height="25" alt="image" src="https://github.com/user-attachments/assets/cd0480b9-cff3-47bb-9e1e-e74cf2dcb940" />

2. Cari 3 file .csv di Internet dan kemudian copykan 3 file tersebut ke direktori yang baru
saja anda buat pada tugas 1 di atas.
  <img width="1543" height="825" alt="image" src="https://github.com/user-attachments/assets/2555b34d-df2f-43e7-94fe-21ea4e7f47b4" />
  <img width="1375" height="190" alt="image" src="https://github.com/user-attachments/assets/05a689ba-c24d-441f-a3a2-ad5d435584b4" />

