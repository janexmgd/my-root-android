# hide root

[back](./README.md)


## bahan

- [lsposed](https://github.com/JingMatrix/Vector) ( pake versi zygisk )

- [HMA](https://github.com/dr-tsng/hide-my-applist)

- [PlayIntegrityFork](https://github.com/osm0sis/PlayIntegrityFork) (optional)


## steps
- saya menggunakan [magisk](https://github.com/topjohnwu/magisk) dan [shamiko](https://github.com/LSPosed/LSPosed.github.io)

    ![magisk-version](./assets/magisk%20version.jpeg)

    ![magisk-setting](./assets/magisk%20setting.jpeg)

    ![magisk-module](./assets/hide%20magisk.jpeg)

    ![shamiko](./assets/shamiko.jpeg)
- install module [lsposed](https://github.com/JingMatrix/Vector) di magisk restart (skip jika sudah install)

- install module [HMA](https://github.com/dr-tsng/hide-my-applist) di [lsposed](https://github.com/JingMatrix/Vector), dan beri checklist seperti ini 
     ![img](./assets/hmaLsPosed.jpeg)

- buka aplikasi [HMA](https://github.com/dr-tsng/hide-my-applist), buat blacklist template dan pilih aplikasi yang mau di hide ( disini saya hide aplikasi magisk, dan beberapa module lsposed) 

    ![template](./assets/hma%20template.jpeg)

- untuk apply hide root nya, kita harus terapkan template hma tadi ke aplikasi target kita 
    ![ex](/assets/proof.jpeg)

- gunakan detection test dahulu untuk memastikan berhasil atau tidaknya
    ![detectiontest](./assets/detection%20test.jpeg)

- tak semua aplikasi dapat menggunakan methode ini 