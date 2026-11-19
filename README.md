# kiw.tech — katalog APK

## Cara menambah aplikasi

1. Buka tab **Releases** -> release **apk**
2. Klik ikon pensil (Edit release)
3. Drag & drop berkas `.apk` ke kotak aset, lalu **Update release**
4. Tunggu maksimal 10 menit — aplikasi muncul sendiri di app kiw.tech

Tidak perlu menyentuh kode, tidak perlu build ulang APK.

## Menentukan kategori

Kategori dibaca dari **nama berkas**. Tulis salah satu dari: `TV`, `Film`,
`Livestreaming`, `Utility`. Kalau tidak ditulis, otomatis masuk **TV**.

Semua bentuk ini dikenali:

```
Film - MovieBox.apk        <- paling mudah dibaca
Film_MovieBox.apk
Film.MovieBox.apk
[Film] MovieBox.apk
MovieBox - Film.apk
MovieBox (Film).apk
```

Nama yang ditampilkan di app tetap bersih (`MovieBox`), penanda kategori dibuang.

Contoh lain:

```
Utility - Root Explorer.apk        -> chip Utility
Livestreaming - Cam Stream.apk     -> chip Livestreaming
BONE TV V.3.2.apk                  -> chip TV (default)
```

Catatan: kata yang kebetulan mengandung nama kategori tidak ikut terbaca —
`Filmora.apk` tetap masuk **TV**, bukan Film.

## Menghapus aplikasi

Hapus asetnya dari release. Katalog ikut bersih pada sinkron berikutnya.

## Kategori bawaan per paket

Beberapa paket sudah dipetakan tetap supaya tidak perlu rename berkas:
AdiXtream, CloudXtream, MovieBox, Otakuray, LOKTV, WeTV, FreeReels -> **Film**;
SmartTube -> **Livestreaming**; ROOT Launcher -> **Utility**; sisanya **TV**.
