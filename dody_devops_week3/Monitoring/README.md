# **Monitoring**

1. Perintah untuk memonitoring sistem, kita dapat melihat penggunaan memory, cpu, swap.

        htop
    ![htop](images/htop.png) <br>

2. Selain htop, bisa juga menggunakan NMON untuk melihat performa sistem.

        nmon (kemudian tekan c untuk melihat performa cpu)
    ![nmon](images/nmon.png) <br>
    ![nmonc](images/nmonc.png) <br>

        ketik d untuk melihat disk.
    ![nmond](images/nmond.png) <br>

3. Melihat seluruh file yang terbuka berdasarkan proses aktif yang berjalan di sistem.

        lsof
    ![lsof](images/lsof.png)

   Menampilkan proses yang dilakukan oleh user

        lsof -u <nama-user>
    ![lsofu](images/lsofu.png)

   Menampilkan proses yang menggunakan port.

        lsof -i :<port>
    ![lsof-i](images/lsof-i.png) <br>

4. Mengetahui daftar proses yang berjalan pada sistem.

        ps -f -u <nama-user>
    ![ps-u](images/ps-u.png)

   Menampilkan seluruh proses secara lengkap.

        ps -aux
    ![ps-aux](images/ps-aux.png) <br>