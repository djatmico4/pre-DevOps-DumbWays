# **Reverse Proxy**

adalah konfigurasi standar yang digunakan untuk mengubah jalur trafic, misal aplikasi menggunakan port 5000 tetapi agar dapat diakses melalui port 80 maka haruns menggunakan reverse proxy.

Untuk webserver, silakan Anda install Nginx dan jalankan. pastikan Nginx run well. <br><br>
![nginx](images/nginx.png) <br>

## Menjalankan aplikasi di web server

1. ***Node app***

   * Pertama silakan nyalakan pm2
   
         pm2 start myapp-nodejs/index.js
      ![startpm2node](images/startpm2node.png) <br>

   * Lalu buat folder di /etc/nginx.

         sudo mkdir app-domain (nama folder)
      ![app-doamin](images/app-domain.png) <br>
      
   * Pindah directory ke app-domain, lalu buat file confignya.

         sudo nano nodejs.dody.conf
      ![nodejsconf](images/nodejsconf.png) <br>

   * Tambahkan folder yang sudah dibuat tadi ke dalam file nginx.conf agar config yang sudah dibuat dapat terbaca oleh nginx.

         sudo nano nginx.conf
      ![addfolderconf](images/addfolderconf.png) <br>

   * Kemudian cek apakah config kita berhasil.

         sudo nginx -t
      ![nginx-t](images/nginx-t.png) <br>

   * Lalu silakan reload nginx.

         sudo systemctl reload nginx
      ![reload](images/reload.png) <br>

   * Karena kita tidak mempunyai server, maka untuk lokal harus menambahkan subdomain di /etc/hosts agar seolah kita mempunyai domain.

         sudo nano /etc/hosts
      ![addhosts](images/addhosts.png)
   
   * Berikut adalah hasilnya <br><br>
      ![resultnode](images/resultnode.png) <br><br>


2. ***Python***

   - Pertama silakan nyalakan pm2 
  
         pm2 start python-app/index.py
      ![startpm2python](images/startpm2python.png) <br>

   - Pindah directory ke app-domain, lalu buat file confignya.

         sudo nano python.dody.conf
      ![pythonconf](images/pyhtonconf.png) <br>

   - Kemudian cek apakah config kita berhasil.

         sudo nginx -t
      ![nginx-t](images/nginx-t.png) <br>

   - Lalu silakan reload nginx.

         sudo systemctl reload nginx
      ![reload](images/reload.png) <br>

   - Seperti halnya pada praktik sebelumnya, tambahkan sub domain ke /etc/hosts

         sudo nano /etc/hosts
      ![addhosts2](images/addhosts2.png)

   - Berikut hasilnya. <br><br>
      ![resultpython](images/resultpython.png) <br><br>

3. ***Go***

  * Untuk Go, nyalakan dahulu nohup.

      nohup ./index &
   ![startnohupgo](images/startnohupgo.png) <br>

  * Pindah directory ke app-domain, lalu buat file confignya.

         sudo nano go.dody.conf
      ![goconf](images/goconf.png) <br>
  
  * Kemudian cek apakah config kita berhasil.

         sudo nginx -t
      ![nginx-t](images/nginx-t.png) <br>

  * Lalu silakan reload nginx.

         sudo systemctl reload nginx
      ![reload](images/reload.png) <br>

  * Seperti halnya pada praktik sebelumnya, tambahkan sub domain ke /etc/hosts

         sudo nano /etc/hosts
      ![addhosts3](images/addhosts3.png) <br>

  * Hasilnya sebagai berikut. <br><br>
      ![resultgo](images/resultgo.png) <br>
      

