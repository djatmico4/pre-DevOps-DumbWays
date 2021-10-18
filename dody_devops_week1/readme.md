# HARVEST CORP

Harvest Corp merupakan perusahaan yang bergerak di bidang e-commerce penjualan berbagai alat dan mesin pertanian.

Pada mulanya Harvest Corp masih mengusung arsitektur monolitik, yang mana kekurangannya adalah sulit melakukan perubahan dan maintenance pada aplikasinya. 

Selain itu untuk servernya sendiri masih menggunakan server on premise. Kita tahu bahwa untuk model ini membutuhkan biaya investasi yang besar untuk inventorynya, pemasangan yang harus di client system, dan yang jelas membutuhkan tim IT profesional untuk mengelolanya.

Kemudian setelah rapat diadakan menghasilkan keputusan bahwa mereka akan akan meng-hire seorang devops engineer. Di sinilah peran saya sebagai seorang devops engineer, mulai menyarankan perusahaan untuk beralih dari monolitik ke arsitektur microservices. Selain aplikasinya yang scalable, secure dan reliable, setiap service memiliki infrastruktur sendiri. Jadi, lebih mudah dalam membuat atau memperbarui aplikasi tanpa memikirkan hubungan/ketergantungan module dengan service yang lain, sehingga update dan maintenance menjadi lebih cepat dan mudah.

Kemudian mengganti server agar memakai Cloud Computing, dan juga saya akan menerapkan pendekatan kultur devops sebagai berikut ;

![flow](images/devops-phase.png)

1. Plan <br>
   Tahap rencana mencakup semua yang terjadi sebelum developer mulai menulis kode. Tool yang digunakan adalah JIRA SOFWARE, merupakan salah satu aplikasi yang dapat mendukung pekerjaan dan penjadwalan dengan baik.
   ![planing](images/jira.png)
<br>

2. Code <br>
   Tahap dimana developer team mulai melakukan coding sesuai plan yang telah dibuat. Di sini tool yang digunakan adalah GitHub
   ![code](images/github.png)
<br>

1. Build <br>
   Merupakan tahap membangun aplikasi, developer team mulai melakukan penggabungan berbagai macam code yang sudah dilakukan. 
<br>

4. Test <br>
   Tahap melakukan pengetesan pada aplikasi yang sudah dibuat.
<br>

5. Release <br>
   Pada tahap ini aplikasi siap untuk ditempatkan di lingkungan produksi. Pada tahap ini, setiap perubahan kode telah melewati serangkaian tes manual dan otomatis. 
<br>

6. Deploy <br>
   Tahap di mana aplikasi sudah siap dirilis ke produksi.
<br>

7. Operate <br>
   Aplikasi sudah rilis dan bisa digunakan oleh customer. Kini tim operasi bekerja keras, memastikan bahwa semuanya berjalan lancar.
<br>

8. Monitor <br>
   Tahap terakhir dari workflow DevOps yakni pemantauan aplikasi.

Workflow di atas juga sama dengan konsep CI/CD (Continuous Integration/Continuous Deployment) berikut ini
![CI/CD](images/ci_cd.png)
<br>

### Selain itu alat-alat yang digunakan antara lain ;

* **Jenkins** <br>
  adalah server otomatisasi open source, membantu mengotomatiskan bagian-bagian pengembangan perangkat lunak yang terkait dengan build, testing dan deploy lalu dapat melakukan proses yang berkelanjutan.
  ![jenkins](images/jenkins.png)
<br>

* **Ansible** <br>
  sebuah open-source software yang dapat digunakan untuk mengotomatiskan banyak proses, seperti pembuatan infrastruktur, manajemen konfigurasi, dan deployment aplikasi. <br>
  ![ansible](images/ansible.png)
<br>

* **Docker** <br>
  platform perangkat lunak yang memungkinkan Anda membuat, menguji, dan menerapkan aplikasi dengan cepat.
  ![docker](images/docker.png)
<br>

* **Amazon Web Services** <br>
  merupakan penyedia layanan cloud yang aman, dan bisa memilih produk sesuai kebutuhan.
  ![aws](images/aws.png)
<br>

* **Kubernetes** <br>
  platform open source untuk mengelola kumpulan kontainer satu sama lain.
  ![kubernetes](images/kubernetes.png)
<br>

* **Grafana & Prometheus** <br>
  Tool yang berfungsi untuk memantau apakah aplikasi berjalan dengan semestinya.
  ![monitoring](images/grafana_prometheus.png)
<br>

* **IP Address** <br>
  IP Public di sini saya gunakan untuk mengakses web dan aplikasinya, sedangkan IP Private saya gunakan untuk berkomunikasi antara web server, database server ataupun storage server agar lebih aman.
<br>

* **Domain** <br>
  Domain sendiri saya memutuskan untuk menyewa di connectindo.id dengan nama harvest.id. 
  
