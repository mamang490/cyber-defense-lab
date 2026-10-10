# Cyber Defense Lab

Dashboard keamanan siber interaktif berbasis HTML, CSS, dan JavaScript. Buka `index.html` di browser untuk menjalankan demo.

## Push ke GitHub dari Android (Termux)

Salin folder `cyber-defense-lab` ke penyimpanan ponsel, misalnya `Download/cyber-defense-lab`. Buat repo GitHub bernama `cyber-defense-lab` terlebih dahulu dan biarkan repo tersebut kosong.

Jalankan di Termux:

```bash
pkg update
pkg install git
termux-setup-storage
cd ~/storage/shared/Download/cyber-defense-lab
git init
git branch -M main
git config user.name "Nama Anda"
git config user.email "Email GitHub Anda"
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME_GITHUB/cyber-defense-lab.git
git push -u origin main
```

Ganti `Nama Anda`, `Email GitHub Anda`, dan `USERNAME_GITHUB` dengan data akun Anda. Jika muncul prompt login, gunakan Personal Access Token (PAT) sebagai password, bukan password akun GitHub.

Jika remote `origin` sudah pernah ditambahkan, ganti perintah `git remote add origin ...` dengan:

```bash
git remote set-url origin https://github.com/USERNAME_GITHUB/cyber-defense-lab.git
```

Jika folder berada di lokasi selain `Download`, ubah jalur pada perintah `cd` sesuai lokasinya.
