# RisunGitLearn
Risun belajar penggunaan git.

# Download Git 
https://www.git-scm.com/download
![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/6d0eb48e-f026-4076-bada-0d9f4dfd9af5)

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
 ![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/de9ba3fa-d1c4-401a-b90e-4c7a11d374e0)


# Masukkan SSH tadi ke Akun Githubmu
- Buka Browser
- Masuk ke Akun Github Mu
- Tekan gambar profilemu lalu cari pengaturan/settings atau via Link (https://github.com/settings/ssh/new)
- Lihat bagian SSH & GPG Keys
- Tekan dan masukkan SSH mu tadi disitu dengan cara pencet "New SSH Key"
- Add SSH Key & done! 
#Sekarang Kamu sudah siap untuk Git


# Mengupload projek yang sudah tersedia di github
- Masuk ke folder lokal di perangkatmu
- Arahkan ke folder yang menjadi tujuan upload ke github
- seperti contoh C:\xampp\htdocs\RisunGitLearn
- Lalu klik kanan di dalam foldernya (tanpa memilih file apapun)
- Klik Git Bash
- ![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/255134a2-6ce3-4a77-983f-2fe0d5468005)

  
#selanjutnya masukkan perintah dibawah
sesuaikan alamatnya dengan repositori kamu sendiri
```bash
git init
```
```bash
git add .
```
```bash
git commit -m "Komentar untuk upload file"
```
```bash
git remote add origin https://github.com/risunCode/RisunGitLearn.git
```
```bash
git push -u -f origin master
```
# Bum taraaa file sudah terupload ke github!
![image](https://github.com/risunCode/RisunGitLearn/assets/155391863/ca3792cf-afc2-4c34-90e3-02d44cd06320)


# Referensi Pembelajaran
- https://github.com/StevenMMortimer/master-to-main/blob/main/README.md
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Create-Git-Repo-Repository-Init-New-Clone-Example-Tutorial
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-push-an-existing-project-to-GitHub
