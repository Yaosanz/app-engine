# Pendeployan Aplikasi dengan Google App Engine

![Google App Engine Logo](https://cloud.google.com/appengine/images/appengine-logo.png)

Selamat datang di panduan pendeployan aplikasi menggunakan Google App Engine di Google Cloud Platform. Dengan menggunakan App Engine, Anda dapat dengan mudah mengelola dan mendeploy aplikasi web Anda tanpa perlu khawatir tentang infrastruktur yang kompleks.

## Langkah-langkah Pendeployan

Berikut adalah langkah-langkah sederhana untuk mendeploy aplikasi Anda:

1. **Persiapkan Lingkungan Pengembangan**
   Pastikan Anda telah menginstal [Google Cloud SDK](https://cloud.google.com/sdk) dan telah mengautentikasi akun Google Cloud Anda.

2. **Konfigurasi Proyek**
   Clone repositori ini dan atur proyek Google Cloud Anda dengan menggunakan perintah berikut:

   ```bash
   gcloud config set project NAMA_PROYEK


# 1. Konfigurasi App Engine
Pilih lingkungan App Engine yang sesuai dengan aplikasi Anda (standard atau flexible). Konfigurasikan file app.yaml untuk menentukan lingkungan dan konfigurasi lainnya.

# 2. Deploy Aplikasi
```
gcloud app deploy
```

## Fitur Utama
- 1. Skalabilitas Otomatis: App Engine secara otomatis menangani peningkatan beban dengan menyesuaikan jumlah instance.
- 2.Pemantauan dan Log: Pantau kinerja aplikasi Anda melalui Google Cloud Console dan akses log untuk pemecahan masalah.
- 3.Pembaruan Mudah: Lakukan pembaruan aplikasi dengan mudah menggunakan perintah gcloud app deploy.

