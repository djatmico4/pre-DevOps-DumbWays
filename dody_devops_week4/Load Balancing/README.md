# **Load Balancing**

adalah proses pendistribusian traffic jaringan ke beberapa server. Ini untuk memastikan salah satu server tidak menanggung terlalu banyak beban permintaan. 

1. Di sini saya memakai contoh aplikasi sederhana node.js sebelumnya dan saya tambahkan menjadi 3 apps (index.js). <br><br>
   ![contohapps](images/contohapps.png) <br>

2. Untuk konfigurasinya, kita buat seperti ini ; <br><br>
    ![setconf](images/setconf.png)

3. Kemudian cek konfigurasinya dan reload nginx.

        sudo nginx -t
        sudo systemctl reload nginx
    ![nginxtandreload](images/nginxtandreload.png) <br>

4. Berikut adalah hasilnya. <br><br>
    ![result1](images/result1.png) <br><br>
    ![result2](images/result2.png) <br><br>
    ![result3](images/result3.png) <br>