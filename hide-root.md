# Hide Root

[← Back](./README.md)

---

## Bahan

- [LSPosed](https://github.com/JingMatrix/Vector) *(gunakan versi Zygisk)*
- [HMA (Hide My Applist)](https://github.com/dr-tsng/hide-my-applist)
- [PlayIntegrityFork](https://github.com/osm0sis/PlayIntegrityFork) *(opsional)*

---

## Steps

### 1. Install Magisk dan Shamiko

Saya menggunakan:

- [Magisk](https://github.com/topjohnwu/magisk)
- [Shamiko](https://github.com/LSPosed/LSPosed.github.io)

#### Screenshot

![magisk-version](./assets/magisk%20version.jpeg)

![magisk-setting](./assets/magisk%20setting.jpeg)

![magisk-module](./assets/hide%20magisk.jpeg)

![shamiko](./assets/shamiko.jpeg)

---

### 2. Install LSPosed

Install module [LSPosed](https://github.com/JingMatrix/Vector) melalui Magisk, lalu restart device.

> Skip langkah ini jika LSPosed sudah terinstall.

---

### 3. Install HMA di LSPosed

Install module [HMA](https://github.com/dr-tsng/hide-my-applist) melalui LSPosed, lalu beri checklist seperti berikut:

![img](./assets/hmaLsPosed.jpeg)

---

### 4. Buat Blacklist Template di HMA

Buka aplikasi HMA, lalu:

- Buat blacklist template
- Pilih aplikasi yang ingin di-hide

Contoh yang saya hide:

- Magisk
- Beberapa module LSPosed

![template](./assets/hma%20template.jpeg)

---

### 5. Terapkan Template ke Aplikasi Target

Untuk mengaktifkan hide root, terapkan template HMA tadi ke aplikasi target.

![ex](./assets/proof.jpeg)

---

### 6. Lakukan Detection Test

Gunakan aplikasi detection test terlebih dahulu untuk memastikan hide root berhasil.

![detectiontest](./assets/detection%20test.jpeg)

---

## Notes

- Tidak semua aplikasi dapat menggunakan metode ini.
- Beberapa aplikasi memiliki proteksi root detection yang lebih ketat.