# Command-Line-Interface
Nama : Riyanda Cavin Sinambela

Jurusan : Teknik Informatika, ITS

1. Membuat directory seperti struktur dibawah:




         Rycs
  
  
            Programming
      
      
               C
       
       
               Java
   
   
            Networking
        
        
               Mikrotik
        
        
      Jawab: 

         mkdir -p Rycs/{Programming/{C,Java},Networking/Mikrotik}

2. Membuat file history.txt yang berisikan semua history perintah yang telah digunakan


   Jawab: 

         touch history.txt

         history > history.txt

3. Melakukan upgrade fitur dengan menggunakan automasi saat terdapat prompt pertanyaan
yes or no


   Jawab:

         sudo apt upgrade

4. Melakukan backup dengan mengcopy source.list ke sebuah file baru yang bernama source.list


   Jawab: 

         sudo cp /etc/apt/sources.list .

         mv sources.list sources.list.backup

5. Melakukan update lalu upgrade secara berurutan dalam satu baris perintah


   Jawab: 

         sudo apt update && sudo apt upgrade

6. Melakukan pencarian sebuah file yang berakhiran".txt" di folder saat ini


   Jawab: 

         find . -name "*.txt" 

7. Menampilkan history perintah yang memilliki kata "sudo" didalamnya


   Jawab: 

         history | grep sudo

8. Membuat file history.txt memiliki role goperti berikut


   User: read, write, n execute // 421 = 7


   Group & Other: read // 4


   Jawab: 

         chmod 744 history.txt

9. Menampilkan somua proses yang sedang berjalan menggunakan perintah ps


   Jawab: 

         ps aux

10. Menampikan proses berdasarkan penggunaan memory terendah ke tertingci dengan
perintah top


      Jawab: 

         top -o -%MEM
