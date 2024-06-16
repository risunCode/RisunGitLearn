# RisunGitLearn
Risun belajar penggunaan git.

# Download Git 
https://www.git-scm.com/download 
![dw-git](https://github.com/risunCode/RisunGitLearn/assets/155391863/1e7747fe-ab17-4e25-be14-56ad10f39c22)

# Instalasi
alah next next aja itu.. basic

# First thing to setup
Buka Git Bash.
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
- ![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/6ff2df2e-2249-41af-92b3-032a58618497)
- Add SSH Key & done!
- #Sekarang Kamu sudah siap untuk Git



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

# Mengupload file lokal ke branch main/master/dll di repositori Github
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

# Mengunduh repositori online ke lokal
- Masuk ke folder lokal yang menjadi target lokasi download
- klik kanan di dalam folder (tanpa memilih apapun)
- Pilih git Bash lalu masukkan command dibawah (sesuaikan dengan repositori target)
```bash
git clone https://alamatrepositoritarget.git
``` 
![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/ef20651e-78b4-407f-8c19-afcafbc74b7b)

# Membuat Branch baru via Git untuk target upload 
- Koneksikan ke repositori online github mu!
```bash
git remote add origin https://github.com/repositorimu.git
```
- cmd untuk melihat repositori yang ada
```bash
git branch
```
- Buat branch baru (sesuaikan nama)
```bash
git checkout -b notmain
```
- push ke branch baru (sesuaikan nama)
```bash
git push -u notmain
```
- Pindah ke branch lain
```bash
git checkout nama-branch
```

# Referensi Pembelajaran
- https://github.com/StevenMMortimer/master-to-main/blob/main/README.md
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Create-Git-Repo-Repository-Init-New-Clone-Example-Tutorial
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-push-an-existing-project-to-GitHub
