# Instalasi Ubuntu Server via VMWare Workstation

1. Pertama download dahulu VMWare Workstation dan Ubuntu Server.

2. Kemudian ubah permissions dari file VMWare Workstation, centang kotak "Make the file executable", klik OK.
    ![1](images/1.png)
    ![2](images/2.png) <br>

3. Jalankan perintah instalasi pada terminal.
    ![3](images/3.png)
Tunggu proses intalasi
    ![4](images/4.png) <br>

4. Langkah berikutnya pilih "accept" kemudian klik "next" dan pilih "no" saja.
    ![5](images/5.png)
    ![6](images/6.png)
    ![7](images/7.png) <br>

5. Instalasi VMWare Workkstation sudah selesai.
    ![8](images/8.png) <br>

6. Berikutnya adalah langkah instalasi ubuntu servernya. Klik "Create a new virtual machine"
    ![9](images/9.png) <br>

7. Untuk konfigurasinya pilih "Typical", klik Next.
    ![10](images/10.png) <br>

8. Kemudian browse file Ubuntu Server yang berformat .iso, klik Next.
    ![11](images/11.png) <br>

9. Langkah berikutnya pilih OS dan versinya, klik Next.
    ![12](images/12.png) <br>

10. Lalu isikan nama dan lokasinya, klik Next.
    ![13](images/13.png) <br>

11. Selanjutnya untuk disk size isikan 20 GB atau sesaui rekomendasiannya dan pilih "Store virtual disk as a single file", klik Next.
    ![14](images/14.png) <br>

12. Kemudian anda bisa melakukan customize hardware, di sini saya akan mengubah network adapternya menjadi bridged.
    ![15](images/15.png)
    ![16](images/16.png) <br>

13. Instalasi Ubuntu Server siap dijalankan, klik "Start up this guest operating system".
    ![17](images/17.png) <br>
    
14. Pilih bahasa sesuai keinginan.
    ![18](images/18.png) <br>

15. Untuk pemilihan layout keyboard, kita biarkan default saja, [Done]
    ![19](images/19.png) <br>

16. Kemudian untuk network connections, di sini saya akan membuatnya menjadi static, automatic DHCP kita ganti manual.
    ![20](images/20.png) <br>

17. Edit IP configurationnya. [Save]
    ![21](images/21.png) <br>

18. Kini IP Addressnya sudah menjadi static. [Done]
    ![22](images/22.png) <br>

19. Untuk proxy address kosongkan saja, [Done]
    ![23](images/23.png) <br>

20. Untuk mirror address, biarkan default saja, [Done]
    ![24](images/24.png) <br>

21. Untuk guided storage dan system summary, langsung [Done] saja.
    ![25](images/25.png)
    ![26](images/26.png) <br>

22. Kemudian isikan profil setup, [Done]
    ![27](images/27.png)

23. Pilih "Isntall OpenSSH", [Done] tunggu hingga proses instalasi selesai.
    ![28](images/28.png)
    ![29](images/29.png)
    ![0](images/30.png) <br>

24. Berikutnya kita coba ssh
    