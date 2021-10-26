# Version Control System

1. Membuat repositori lokal.

        git init
    ![init](images/init.png)
    ![init2](images/init2.png) <br>

2. Menambahkan file atau folder ke repository.

        git add <nama-file>
    ![add](images/add.png)

   Menambahkan file dengan berdasarkan ekstensinya.

        git add *.<file-ekstensi>
    ![add2](images/add2.png)

   Menambahkan keseluruhan file dan folder.

        git add .
    ![add3](images/add3.png) <br>

3. Menghapus file dari repositori.

        git rm --cached <nama-file>
    ![rm](images/rm.png)

   Menhapus folder yang berisi banyak file.

        git rm --cahced <nama-folder>/ -r
    ![rm2](images/rm2.png) <br>

4. Melihat status file atau folder pada repositori lokal.

        git status
    ![status](images/status.png) <br>

5. Membuat commit pada repositori.

        git commit -m <pesan>
    ![commit](images/commit.png) <br>

6. Membuat branch baru atau me-rename baranch yang sudah ada.

        git branch -M <nama-branch-baru>
    ![bracnh](images/branch.png)

   Melihat branch yang sudah dibuat.

        git branch -a
    ![branch2](images/branch2.png) <br>

7. Berpindah ke branch lain.

        git checkout <nama-branch>
    ![checkout](images/checkout.png) <br>

8. Menambahkan repositori ke Github.

        git remote add <nama-remote> <url-remote>
    ![remote](images/remote.png)

   Mengubah nama remote.

        git remote rename <nama-remote-lama> <nama-remote-baru>
    ![rmeote2](images/remote2.png) <br>

9. Mengirim/memasukkan ke Github
    
        git push <nama-remote> <nama-branch>
    ![psuh](images/push.png) <br>

10. Mengambil repositori dari Github.

        git pull <nama-remote> <nama-branch>
    ![pull](images/pull.png) <br>

11. Meng-copy repositori dari remote ke lokal

        git clone <url-remote> [nama-dir] 
        (opsional nama direktori yang akan dibuat. Jika kita tidak berikan nama direktori, maka akan otomatis menggunakan nama repositori)
    ![clone](images/clone.png)


