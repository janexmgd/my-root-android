# Android Device Identity

[← Back](./README.md)

---

## Bahan

- Android dengan akses root *(saya menggunakan Magisk)*
- [LSPosed](https://github.com/JingMatrix/Vector) *(gunakan versi Zygisk)*
- [DeviceSpoofLabs-Hooks](https://github.com/yubunus/DeviceSpoofLab-Hooks)

---

## Steps

### 1. Aktifkan LSPosed

Aktifkan module [LSPosed](https://github.com/JingMatrix/Vector) di Magisk, lalu restart device.

---

### 2. Aktifkan DeviceSpoofLabs-Hooks

Aktifkan module [DeviceSpoofLabs-Hooks](https://github.com/yubunus/DeviceSpoofLab-Hooks), lalu beri checklist pada aplikasi yang ingin di-hook.

Setelah itu, restart device.

![img](./assets/deviceSpoofLabs.jpeg)

---

### 3. Generate Device Identity Baru

Setiap ingin membuat device identity baru:

1. Hapus data aplikasi target
2. Hapus data aplikasi [DeviceSpoofLabs-Hooks](https://github.com/yubunus/DeviceSpoofLab-Hooks)
3. Buka aplikasi DeviceSpoofLabs-Hooks agar otomatis generate identity baru
4. Setelah selesai, buka kembali aplikasi target

> Tidak perlu restart untuk menerapkan perubahan.

#### Screenshot

**Before**

![before](./assets/before.jpeg)

**After**

![after](./assets/after.jpeg)

---

## Inti Langkah

Singkatnya:

1. Hapus data aplikasi target
2. Hapus data DeviceSpoofLabs-Hooks
3. Buka DeviceSpoofLabs-Hooks untuk generate device ID baru
4. Buka kembali aplikasi target