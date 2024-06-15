# RisunGitLearn
Risun belajar penggunaan git.

# Download Git 
https://www.git-scm.com/download 
![dw-git](https://github.com/risunCode/RisunGitLearn/assets/155391863/1e7747fe-ab17-4e25-be14-56ad10f39c22)

# Instalasi
alah next next aja itu.. basic

# First thing to setup
Atur Nama dan alamat email.
```bash
git config --global user.name "namaKamu"
```
```bash
git config --global user.email email@kamu.id
```
```bash
git config --global color.ui true
```   

#untuk mengecek perubahan
```bash
git config --list
```    

# Atur SSH
- Buka GIT GUI
- Arahkan ke bagian Help > SSH > Generate Key
- Masukkan Sandi untuk SSH (lalu copy hasil generated SSH) 
![ssh](https://github.com/risunCode/RisunGitLearn/assets/155391863/8a8ce967-aa98-4b6e-9357-9c7c0e0f247f)

# Masukkan SSH tadi ke Akun Githubmu
- Buka Browser
- Masuk ke Akun Github Mu
- Tekan gambar profilemu lalu cari pengaturan/settings atau via Link (https://github.com/settings/ssh/new)
- Lihat bagian SSH & GPG Keys
- Tekan dan masukkan SSH mu tadi disitu dengan cara pencet "New SSH Key"
- Add SSH Key & done!
![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/6ff2df2e-2249-41af-92b3-032a58618497)
#Sekarang Kamu sudah siap untuk Git


# Mengupload projek yang sudah tersedia di github
- Masuk ke folder lokal di perangkatmu
- Arahkan ke folder yang menjadi tujuan upload ke github
- seperti contoh C:\xampp\htdocs\RisunGitLearn
- Lalu klik kanan di dalam foldernya (tanpa memilih file apapun)
- Klik Git Bash 
![dowoda](https://github.com/risunCode/RisunGitLearn/assets/155391863/26c03196-2324-4b6d-912f-ff6de63d8cea)

  
#atur agar menjadi default main
```bash
git config --global init.defaultBranch main
```

# Mengupload file lokal ke branch main/master/dll ke repositori Github
sesuaikan dengan alamat repositori kamu sendiri
```bash
git init
```
```bash
git add .
```
```bash
git branch -M main
```
```bash
git commit -m "first commit"
```
```bash
git remote add origin https://github.com/risunCode/RisunGitLearn.git
```
```bash
git push -u origin main
``` 
# Bum taraaa file sudah terupload ke github!
![ddwd](https://github.com/risunCode/RisunGitLearn/assets/155391863/f061ad35-c931-42b9-94a7-82c9e390ed04)


# Referensi Pembelajaran
- https://github.com/StevenMMortimer/master-to-main/blob/main/README.md
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Create-Git-Repo-Repository-Init-New-Clone-Example-Tutorial
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-push-an-existing-project-to-GitHub
