# Basic Linux Commands

1. Mencari path dari direktori yang anda gunakan saat ini.

         pwd
      ![pwd](images/pwd.png) <br>

2. Membuat folder baru.
         
         mkdir <nama-folder>
      ![mkdir](images/mkdir.png)

   Contoh membuat beberapa folder sekaligus.
   
         mkdir <nama-folder nama-folder2 nama-folder3>
   ![mkdir2](images/mkdir2.png) <br>

3. Melihat isi dari direktori.

         ls
      ![mkdir](images/mkdir2.png)

   Berikut contoh menampilkan file atau folder hidden. 

         ls -la
      ![ls](images/ls-la.png) <br>

4. Masuk ke dalam direktori atau folder menggunakan cd.

         cd <nama-directory/folder>
      ![cd](images/cd.png) <br>

   Keluar dari current directory ke parent directory.

         cd ..
      ![cd2](images/cd2.png) <br>

5. Copy file.

         cp <file-lama> <file-baru>
      ![cp](images/cp.png) <br>

   Untuk meng-copy folder dan semua isinya.

         cp -r <folder-lama> <folder-baru> 
      ![cp2](images/cp2.png) <br>

6. Membuat file.
   
         touch <nama-file>
      ![touch](images/touch.png) <br>

7. Melihat isi sebuah file.

         cat <nama-file>
      ![cat](images/cat.png) <br>

8. Menghapus file.

         rm <nama-file>
      ![rm](images/rm.png)

   Menghapus folder dan beserta isinya.

         rm -r <nama-folder>
      ![rm2](images/rm2.png) <br>

9.  Memindah/rename file atau folder.

         mv <file/foldr-lama> <file/folder-baru>
      ![mv](images/mv.png) <br>

10. Mencari berbagai jenis file menggunakan perintah find.
        Anda dapat menggunakan deskriptor berikut untuk menentukan jenis file.
    ![type](images/type.png)

         find </your/path -type f -name nama-file>
      ![find](images/find.png) <br>

11. Mencari pattern atau kata pada sebuah file text yang sudah dibuat.

         grep <text yang dicari> <nama-file>
      ![grep](images/grep.png) <br>

12. Perintah yang memungkin anda untuk menjalankan program sebagai superuser atau pengguna lain.
    
         sudo <execution command>
      ![sudo](images/sudo.png) <br>

13. Membuat user baru.

         sudo adduser <nama-user-baru>
      ![adduser](images/addusr.png) <br>

14. Berganti user.

         su <nama-user>
      ![su](images/su.png) <br>

15. Menghapus user.
    
         sudo deluser <nama-user>
      ![deluser](images/deluser.png) <br>

16. Memberikan hak akses superuser pada user lain.

         sudo usermod -aG <group> <user>
      ![usermod](images/usermod.png) <br>

17. Memberikan mode (hak akses) file dan direktori.

         sudo chmod <mode> <file atau folder>
      ![chmod](images/chmod.png) <br>

18. Memberikan hak akses file atau folder pada user lain

         sudo chown <options> <user:group> <nama-file/folder>
      ![chown](images/chown.png) <br>

19. Menghapus user.

         sudo deluser <nama-user>
      ![deluser](images/deluser.png) <br>

20. Mengecek koneksi server.

         ping <server>
      ![ping](images/ping.png) <br>

21. Review atau melihat command yang pernah dipakai.

         history
      ![history](images/history.png) <br>

22. Mengompres dan mengekstrak file.

         zip -r <archivename.zip> <file to zip>
      ![zip](images/zip.png)

         unzip <archivename.zip>
      ![unzip](images/unzip.png) <br>

23. Mengetahui nama host/network, juga melihat IP address dengan menambahkan -i atau -I di akhir command.

         hostname -i
            atau
         hostname -I
      ![hostname](images/hostname.png) <br>

24. Salah satu fungsi command echo adalah memindahkan beberapa data ke dalam satu file, di sini saya contohkan menambahkan teks.

         echo <teks> >> <file.txt>
      ![echo](images/echo.png) <br>

25. Membersihkan jendela terminal.

         clear
      ![clear](images/clear.png)
   




    
