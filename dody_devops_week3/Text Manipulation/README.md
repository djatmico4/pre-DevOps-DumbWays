# **Text Manipulation**

1. Melihat konten atau isi file.

        cat <nama-file>
    ![cat](images/cat.png)

   Membuat file beserta isinya.

        cat > <file-isi>
    ![cat2](images/cat2.png)

   Mengaabungkan isi file.

        cat <nama-file1> <nama-file2> > <nama-file3>
    ![cat3](images/cat3.png) <br>

2. Memanipulasi teks dasar pada file.

        sed -i 's/<teks-awal>/<teks-pengganti>/g' <nama-file>
    ![sed](images/sed.png) <br>

3. Melakukan pencarian sebuah kata pada sebuah file yang sudah dibuat.

        grep <kata> <nama-file>
    ![grep](images/grep.png)

   Menghitung jumlah kata yang dicari.

        grep -c <kata> <nama-file>
    ![grepc](images/grepc.png)

   Menampilkan semua file yang berisikan kata yang dicari.

        grep <kata> *
    ![grap*](images/grep*.png) <br>

4. Mengurutkan data secara ascending.

        sort <nama-file>
    ![sort](images/sort.png)

   Mengurutkan secara descending.

        sort -r <nama-file>
    ![sort-r](images/sort-r.png) <br>

5. Menambahkan/mencetak string atau pesan.

        echo <"kata yang ingin dicetak">
    ![echo](images/echo.png)

   Menambahkan string atau pesan pada file.

        echo <"kata yang akan ditambahkan"> >> <nama-file>
    ![echo2](images/echo2.png)

   Mengganti semua isi data pada suatu file.

        echo <"kata yang akan digunakan sebagai pengganti"> > <nama-file>
    ![echo3](images/echo3.png) <br>

6. Mencetak baris pertama (10 baris secara default) dari satu atau lebih file.

        head <nama-file>
    ![head](images/head.png)

   Menampilkan jumlah baris tertentu.

        head -n <nama-file>
    ![headn](images/headn.png) <br>

7. Menampilkan bagian terakhir.

        tail <nama-file>
    ![tail](images/tail.png) <br>
    ![tail2](images/tail2.png)

   Menampilkan jumlah baris tertentu.

        tail -n <nama-file>
    ![tailn](images/tailn.png) <br>

8. Menampilkan konten atau file dari suatu perintah dalam satu halaman.

        less <nama-file>
    ![less](images/less.png) <br>
    ![less2](images/less2.png) <br>

9. Mencari perbedaan antara dua buah file.

        diff <nama-file1> <nama-file2>
    ![diff](images/diff.png) <br>