# KODIK - Aplikasi Android

Ini adalah versi Android native dari marketplace KODIK, yang dibangun dengan Kotlin dan Jetpack Compose.

## Otomatisasi Build dengan GitHub Actions

Proyek ini dikonfigurasi dengan alur kerja GitHub Actions (`.github/workflows/build_apk.yml`). Setiap kali ada perubahan yang di-push ke branch `main`, GitHub akan secara otomatis:
1. Menyiapkan lingkungan build Android.
2. Menjalankan proses kompilasi.
3. Menghasilkan file `app-debug.apk`.

File APK yang sudah jadi dapat diunduh dari tab **Actions** di halaman repositori GitHub.

## Cara Menjalankan Secara Lokal

1. Buka proyek ini di Android Studio.
2. Buka file `app/build.gradle.kts`.
3. Ganti placeholder `"MASUKKAN_API_KEY_ANDA_DI_SINI"` dengan API key Gemini Anda yang valid.
4. Sinkronkan proyek dengan file Gradle.
5. Jalankan aplikasi pada emulator atau perangkat Android fisik.
