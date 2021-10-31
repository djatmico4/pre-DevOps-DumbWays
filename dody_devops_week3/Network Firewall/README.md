# **Network Firewall**

Iptables merupakan salah satu tools firewall pada sistem operasi Linux. Fungsi iptables adalah mengamankan jaringan dengan melakukan penyaringan trafik pada server. Selain mengatur lalu lintas jaringan, anda juga mampu mengelola jenis paket yang dapat diterima, mengatur trafik berdasarkan asal dan tujuan data, mengelola port, dan lainnya. <br>

Ufw adalah singkatan dari Uncomplicated Firewall sebuah aplikasi front-end dari iptables yang ringan, powerful dan sangat mudah digunakan untuk mengatur firewall. <br>

* Melakukan instalasi ufw, jalankan perintah berikut :

        sudo apt install ufw -y
    ![ufw](images/ufw.png) <br>

* Memblokir semua akses yang masuk

        sudo ufw default deny incoming
    ![ufw2](images/ufw2.png)

* Membuka semua akses yang keluar

        sudo ufw default allow outgoing
    ![ufw2](images/ufw2.png) <br>

* Kemudian buka beberapa port umum seperti ssh, https, dll. 

        sudo ufw allow "OpenSSH"
        sudo ufw allow "Nginx Full"
    ![allow](images/allow.png) <br>

* Selain itu anda bisa cek sendiri aplikasi apa saja yang ada di daftar UFW dengan perintah berikut :

        sudo ufw app list
    ![appl](images/appl.png) <br>

* Mengaktifkan firewall.

        sudo ufw enable
    ![enable](images/enable.png) <br>

* Menonaktifkan firewall.

        sudo ufw disable
    ![disable](images/disable.png) <br>

* Mengecek status firewall

        sudo ufw status
    ![status](images/status.png) <br>


