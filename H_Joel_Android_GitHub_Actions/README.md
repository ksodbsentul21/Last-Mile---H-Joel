# H Joel Last Mile - Android APK via GitHub Actions

Project Android WebView untuk aplikasi Last Mile H Joel Logistics.

## Cara build APK di GitHub
1. Buat repository baru atau gunakan repository khusus APK.
2. Upload SEMUA isi folder project ini ke root repository. Folder `.github` harus ikut ter-upload.
3. Commit ke branch `main`.
4. Buka tab **Actions**.
5. Pilih workflow **Build H Joel APK**.
6. Klik **Run workflow** > **Run workflow**.
7. Tunggu sampai status hijau.
8. Buka hasil run tersebut.
9. Di bagian **Artifacts**, klik **H-Joel-Last-Mile-APK**.
10. ZIP artifact akan ter-download. Ekstrak dan install `H-Joel-Last-Mile.apk` di Android.

## Catatan Android
- Saat pertama membuka scanner/foto, Android akan meminta izin kamera. Pilih **Izinkan**.
- APK debug dapat dipasang langsung untuk penggunaan internal/test.
- Untuk distribusi resmi/Play Store sebaiknya gunakan release APK/AAB yang ditandatangani keystore.

## Update aplikasi
Jika `index.html` atau file aplikasi diubah, commit/push ke branch `main`. GitHub Actions otomatis build APK baru.

## Logo Final
Launcher icon menggunakan logo lengkap H JOEL LOGISTICS yang diberikan pengguna, diposisikan di tengah bidang putih persegi agar seluruh logo tetap terlihat pada launcher Android. Nama aplikasi: LM - H Joel. Nama APK hasil Actions: LM - H Joel.apk.
