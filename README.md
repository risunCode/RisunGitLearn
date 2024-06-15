# RisunGitLearn
Risun belajar penggunaan git.

# Download Git 
https://www.git-scm.com/download 

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

  
#selanjutnya masukkan perintah dibawah
sesuaikan alamatnya dengan repositori kamu sendiri
```bash
echo "# RisunGitLearn" >> README.md
```
```bash
git init
```
```bash
git add README.md
```
```bash
git commit -m "first commit"
```
```bash
git branch -M main
```
```bash
git remote add origin https://github.com/risunCode/RisunGitLearn.git
```
```bash
git push -u origin main
``` 
# Bum taraaa file sudah terupload ke github! 


# Referensi Pembelajaran
- https://github.com/StevenMMortimer/master-to-main/blob/main/README.md
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Create-Git-Repo-Repository-Init-New-Clone-Example-Tutorial
- https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-to-push-an-existing-project-to-GitHub
