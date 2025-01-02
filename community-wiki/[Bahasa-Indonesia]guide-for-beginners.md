**Terakhir diperbarui pada 28/SEP/2024.**



### [Untuk lebih banyak sumber daya seperti ini, periksa wiki subreddit lengkap.](https://reddit.com/r/revancedextended/w/index)

---

### Tambalan mungkin tidak stabil untuk sementara waktu. Jika Anda mengalami masalah, periksa postingan terbaru untuk situasi serupa.

---

**[Berasal dari ReVanced? Gunakan RVX Manager yang dibuat khusus untuk patch ReVanced Extended!](https://github.com/inotia00/revanced-manager/releases/latest)**



___





### **Hal Yang Perlu Diketahui Sebelum Anda Mulai**



* Panduan ini dimaksudkan sebagai titik awal yang terperinci bagi pengguna pertama kali.




* Baca [Pertanyaan yang Sering Diajukan](https://www.reddit.com/r/revancedextended/wiki/faq/).





* Panduan ini ditujukan untuk instalasi non-root.





* Panduan ini akan menggunakan metode patching RVX Manager. Periksa [dokumentasi](https://github.com/inotia00/revanced-documentation#revanced-extended-documentation) untuk info tentang metode patching lainnya.





* Periksa [bagian pemecahan masalah](https://www.reddit.com/r/revancedextended/wiki/troubleshooting/) jika Anda mengalami kebuntuan selama panduan ini.







# **1. Persyaratan:**





* Perangkat Anda harus menjalankan Android 8.0 atau lebih baru.





* Arsitektur perangkat Anda harus arm64-v8a, armeabi-v7a, atau x86-64. (Anda akan mengetahui apakah itu suatu saat)







#### **Mengunduh GmsCore, APK untuk ditambal, & Manajer RVX**


Unduh dan instal APK **RVX Manager** dari [di sini](https://github.com/inotia00/revanced-manager/releases/latest). Ini adalah cabang inotia00 dari Manajer ReVanced resmi.

> Jika Anda mendapat pesan kesalahan *"Aplikasi tidak diinstal karena aplikasi tidak kompatibel dengan perangkat Anda."* itu berarti perangkat Anda tidak didukung oleh Manajer RVX. Lihat edisi 1 di [panduan pemecahan masalah umum](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/general-troubleshooting.md) untuk instruksi.





Unduh, tetapi **jangan** instal APK yang ingin Anda patch dari apkmirror.com:

**YouTube**: [`v19.16.39` (`nodpi`) APK](https://www.apkmirror.com/apk/google-inc/youtube/youtube-19-16-39-release/youtube-19-16-39-android-apk-download/)

**YT Music**: [`v7.16.53` APK](https://www.apkmirror.com/apk/google-inc/youtube-music/youtube-music-7-16-53-release/#downloads). Akan ada [2-4 varian](https://i.imgur.com/KRmvhWh.png) APK, masing-masing untuk arsitektur yang berbeda. Untuk memilih APK yang benar, buka RVX Manager dan buka pengaturan. Di bagian bawah pengaturan akan mencantumkan arsitektur yang didukung perangkat Anda.

**Reddit**: [`v2024.17.0` (`nodpi`) APK](https://www.apkmirror.com/apk/redditinc/reddit/reddit-2024-17-0-release/reddit-2024-17-0-2-android-apk-download/)



> Jika Anda ingin mempelajari lebih lanjut cara menemukan APK yang benar tanpa bergantung pada panduan ini, lihat bagian 2 dari [panduan info pengaturan](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup).





Jika menambal YouTube atau YT Music: > **GmsCore** diperlukan agar YouTube dan YT Music yang di-patch dapat berjalan. Jika Anda belum menginstal GmsCore, unduh dan instal [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest). (Jika Anda menggunakan perangkat Hauwei, pastikan untuk memilih unduhan khusus untuk perangkat Anda.)











# **2. Menambal**





Buka Manajer RVX. Perangkat Anda mungkin membuka halaman pengaturan untuk memilih aplikasi mana yang memiliki izin untuk menginstal aplikasi yang tidak dikenal. Temukan Manajer RVX dan berikan izin.





Kemudian di Manajer, buka Patcher > Pilih aplikasi.





Tekan "**Penyimpanan**" [seperti yang ditunjukkan pada gambar ini](https://imgur.com/a/vx64z3S).





Pilih file APK yang baru saja Anda unduh dari APKMirror dari folder unduhan Anda.





Aplikasi akan dipilih dan jika ini adalah pertama kalinya Anda menambal, daftar tambalan Default akan dipilih. Jika Anda ingin memastikan patch Default dipilih, ketuk patch yang dipilih dan tekan tombol Default di bagian atas menu pilihan patch.





Jika Anda tidak ingin menggunakan pilihan Default, Anda **harus** setidaknya menyertakan patch `Dukungan GmsCore`.





> [Kunjungi repositori ini untuk mengetahui fungsi patchnya!](https://github.com/ReVanced-Extended-Community/Patches-Documentation#patches-documentation) (work-in-progress)





Setelah selesai memilih patch, tekan "**Done**" lalu tekan "**Patch**".





Tunggu hingga patching selesai. Biasanya memakan waktu 2-5 menit. Jika Anda keluar dari aplikasi, aplikasi mungkin dibatalkan. Pastikan tidak ada kesalahan yang terjadi selama langkah ini.







# **3. Menginstal**





> Ketika patching selesai, Anda dapat menyimpan APK sebagai file sehingga Anda dapat menyimpannya nanti jika Anda kesulitan menginstalnya atau ingin membagikannya. Untuk melakukannya, ketuk ikon simpan di sudut kiri bawah layar seperti yang ditunjukkan [di sini](https://imgur.com/a/FKD0okE).





Tekan "Instal" dan tunggu hingga instalasi selesai. Anda mungkin mendapat pesan yang mengatakan bahwa instalasi diblokir karena itu adalah aplikasi yang tidak dikenal. Ketuk "**Lebih detail**" lalu "**Tetap instal**" seperti yang ditunjukkan [di sini](https://imgur.com/a/iLP2m7l).







#### **Opsional - Pengaturan Tambahan:**

Ada beberapa pengaturan tambahan yang dapat Anda lakukan untuk membuat aplikasi yang dipatch menjadi lebih baik! Hal-hal seperti membuka tautan YouTube di aplikasi YouTube yang ditambal, atau menyiapkan fitur pengunduhan di YouTube RVX dan YT Music RVX. Lihat bagian 2 dan 3 dari [panduan info pengaturan](https://github.com/ReVanced-Extended-Community/Community-Guides/blob/main/community-wiki/patching%20%26%20setup%20info.md#2-general-info-for-patching-and-feature-setup) untuk informasi tentang menyiapkan hal-hal semacam ini.


**Anda sudah selesai!**



___







# **Info Lebih Lanjut/Pemecahan Masalah**





Periksa [bagian pemecahan masalah](https://www.reddit.com/r/revancedextended/wiki/troubleshooting/) untuk bantuan.




Lihat [situs ini](https://kazimmt.github.io/#revanced-extended-features) untuk melihat fungsi semua pengaturan ReVanced Extended! (Perhatikan bahwa ini sedang dalam proses)
