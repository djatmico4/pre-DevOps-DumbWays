# **Membuat Simple Apps**

Berikut ini kita akan membuat aplikasi sederhana menggunakan node.js, python dan juga Go.

### **Node.js**

1. Langkah instalasi node.js, masukan perintah berikut ;

        curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    ![nvm](images/nvm.png) <br>

        jalankan exec bash dan cek versi nvmnya
    ![exec](images/exec.png) <br>
        
    Install node nya

        nvm install 16 (versinya)
    ![node](images/node.png) <br>

    Cek versi node dan npm

        node -v
        npm -v
    ![cekvernodenpm](images/cekvernodenpm.png) <br>

        nvm use 16 (pilih versi nvm apabila install lebih dari satu versi)
    ![nvm2](images/nvm2.png) <br>

2. Kemudian kita coba membuat aplikasi sederhananya.

        - buat folder baru : mkdir myapp-nodejs
        - masuk ke directory tersebut : cd myapp-nodejs/
        - buat file package.json : npm init -y
    ![egapp](images/egapp-node-express.png) <br>
    
3. Install plugin express.

        npm install express --save
    ![express](images/express.png) <br>

        Melihat isi package.jason : cat package.json
    ![install-express](images/install-express.png) <br>

4. Buat file index.js

        nano index.js
    ![index](images/indexjs.png)
    
    Lakukan perubahan config sesuai kebutuhan, misal di sini saya menuliskan kata Hello DumbWays, lalu simpan dan keluar dari nano. <br>

5. Jalankan aplikasi node.js

        node index.js (nama-aplikasi)
    ![runappnode](images/runappnode.png) <br>
    ![resultappnode](images/resultappnode.png) <br> <br>


### **Python**

1. Pertama update dan upgrade sistem. Python sudah ada secara default tinggal cek saja : python3 -V.

        install package manager : sudo apt install python3-pip
    ![installpy-pip](images/installpy-pip.png) <br>

2. Install flask.

        pip install flask
    ![installflask](images/installflask.png) <br> 

3. Buat sebuah folder dan file index.py

        mkdir python-app
    ![pyfolder](images/pyfolder.png) <br>

        nano index.py
    ![nanopy](images/nanopy.png) <br>

    Lakukan perubahan config sesuai kebutuhan, misal di sini saya menuliskan kata Welcome to DumbWays, lalu simpan dan keluar dari nano. <br>

4. Jalankan aplikasi python3

        python3 index.py (nama-aplikasi)
    ![runpy](images/runpy.png) <br>
    ![resultapppy](images/resultapppy.png)<br> <br>


### **Go**

1. Download Go terlebih dahulu

        wget https://golang.org/dl/go1.17.3.linux-amd64.tar.gz && sudo su
    ![golang](images/golang.png) <br>

    Ekstrak dan copy data

        rm -rf /usr/local/go && tar -C /usr/local -xzf go1.17.3.linux-amd64.tar.gz
    ![extandnco](images/extandco.png) <br>

    Masukkan path Go pada bashrc dan jalankan exec bash

        nano .bashrc
    ![pathandver](images/pathandver.png) <br>    
        
        exec bash
    ![execbash](images/execbash.png) <br>

    Lakukan verifikasi installasi

        go version
    ![goversion](images/goversion.png) <br>

2. Membuat aplikasi sederhana. Pertama buat sebuah folder.

        mkdir myapp-golang
    ![gofolder](images/gofolder.png) <br>

    Pindah direktori dan buat sebuah file index.go.

        cd myapp-golang/
    ![cdgo](images/cdgo.png) <br>

        nano index.go
    ![nanogo](images/nanogo.png) <br>

    Lakukan perubahan config sesuai kebutuhan, misal di sini saya menuliskan kata Hi there, I'm Dody !, lalu simpan dan keluar dari nano. <br>

3. Jalankan aplikasi golang

        go run index.go

    Jika ingin dibuild

        go build index.go (nama-aplikasi)
        lalu jalankan : ./index
    ![resultappgo](images/resultappgo.png) <br>


    