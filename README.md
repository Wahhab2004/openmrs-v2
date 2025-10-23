# 🏥 DOKUMENTASI PENGGUNAAN OPENMRS VIA LOKAL  
**Disusun oleh:** Wahhab Awaludin (CEO)

---

## 📦 1. Installasi

1. Kunjungi tautan di bawah untuk _set up an instance of o3_ (openmrs):
   
   👉 [Set Up an Instance of O3](https://openmrs.atlassian.net/wiki/spaces/docs/pages/150930190/Set+Up+an+Instance+of+O3)

3. Ikuti panduan pada bagian **Using OpenMRS SDK** dan pastikan seluruh *prerequisites* telah dipenuhi sebelum instalasi.  
   Beberapa kebutuhan umum meliputi:
   - Java (versi 11 atau sesuai rekomendasi)
   - Maven
   - MySQL / MariaDB
   - OpenMRS SDK

---

## 🚀 2. Akses Aplikasi

1. Jalankan aplikasi OpenMRS di lokal dengan perintah _mvm openmrs-sdk:run_.
2. Akses melalui browser pada alamat berikut:
   
   🔗[https://localhost:8080/openmrs](https://localhost:8080/openmrs)
  
4. Masukkan kredensial berikut untuk login:
   ```bash
   Username: admin
   Password: admin123

## ⚙️ 3. Instalasi Modul Tambahan

1. Setelah berhasil login ke dashboard OpenMRS, unggah file modul [.omod](https://drive.google.com/file/d/12i6hbXTSg8yd8X_xK69-k0C4EzU_NixA/view?usp=sharing) yang telah diunduh ke direktori Modules pada aplikasi OpenMRS. 
2. Setelah modul berhasil diinstal:
    Matikan aplikasi OpenMRS.
3. Jalankan kembali aplikasi agar modul dapat dimuat sepenuhnya.

---

## 🧩 4. Verifikasi Modul Webservice
1. Masuk ke menu Administration di dashboard.
2. Pastikan modul Webservice sudah muncul dan berstatus Active.

---

## 🧪 5. Pengujian CRUD via Postman
1. Gunakan koleksi [Postman](https://drive.google.com/file/d/1MmJoC2jKlxeRjFPYct4Azq7fgil57xXg/view?usp=sharing) yang telah disediakan untuk menguji operasi:
Create (POST)
Read (GET)
Update (PUT)
Delete (DELETE)
2. Pastikan setiap endpoint berjalan dengan baik dan memberikan response sesuai ekspektasi.

---

✅ Selesai!

Aplikasi OpenMRS kini telah berhasil dijalankan di lingkungan lokal dan siap digunakan untuk kebutuhan pengembangan serta pengujian lebih lanjut.

