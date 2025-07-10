Jasa setting mikrotik : +62822-3348-3221

---

# 📘 Panduan Downgrade MikroTik RouterOS v7 ke v6.49.18 (mipsbe)

---

## 1️⃣ Download File RouterOS v6.49.18

✅ Klik link ini:
[https://download.mikrotik.com/routeros/6.49.18/routeros-mipsbe-6.49.18.npk](https://download.mikrotik.com/routeros/6.49.18/routeros-mipsbe-6.49.18.npk)

Simpan filenya di komputer.

---

## 2️⃣ Upload File ke MikroTik

1. Buka **Winbox**
2. Login ke router
3. Buka menu **Files**
4. Seret file `routeros-mipsbe-6.49.18.npk` ke jendela Files
   ✅ Pastikan file sudah muncul di daftar Files.

---

## 3️⃣ Jalankan Downgrade

1. Buka menu **System > Reboot**
2. Klik **Yes** untuk konfirmasi reboot

Router akan otomatis mendeteksi file versi lama dan melakukan downgrade.

---

## 4️⃣ Tunggu Router Restart

🕒 Tunggu ±3–5 menit sampai router hidup kembali.
Jangan cabut listrik!

---

## 5️⃣ Cek Versi

Login lagi, lalu di Terminal ketik:

```
/system resource print
```

Harus tampil:

```
version: 6.49.18
```

✅ Downgrade selesai!

---

## ⚠️ Tips Penting

* **Jangan cabut power saat proses.**
* Setelah downgrade, kalau konfigurasi error, lakukan reset:

  ```
  /system reset-configuration no-defaults=yes
  ```

  (Semua konfigurasi akan terhapus)

---

Kalau mau saya siapkan file PDF rapi (judul + langkah + link download aktif), beri tahu, nanti saya buatkan.
