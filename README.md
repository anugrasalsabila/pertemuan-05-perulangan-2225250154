# Pertemuan 05 Perulangan Python

**Nama:** Intan Anugra Salsabila
**NIM:** 2225250154
**Kelas:** 2F

## Tujuan

Menggunakan perulangan `for` dan `while` untuk menyelesaikan masalah iteratif.

## Cara Menjalankan

Untuk menjalankan program Kuis 2 Deret Aritmetika, gunakan perintah:

```bash
python kuis/kuis2_deret_aritmetika.py
```

## Algoritma Kuis 2

Langkah-langkah program deret aritmetika:

1. Menampilkan judul program.
2. Meminta pengguna memasukkan suku pertama `a`.
3. Meminta pengguna memasukkan beda `d`.
4. Meminta pengguna memasukkan banyak suku `n`.
5. Memeriksa apakah `n` merupakan bilangan positif.
6. Menyimpan suku pertama sebagai suku yang akan ditampilkan.
7. Melakukan perulangan sebanyak `n` kali.
8. Pada setiap perulangan, menampilkan nomor suku dan nilai sukunya.
9. Menambahkan nilai suku ke variabel jumlah.
10. Menghitung suku berikutnya dengan menambahkan beda `d`.
11. Setelah perulangan selesai, menampilkan jumlah seluruh suku.
12. Jumlah deret dihitung melalui proses perulangan, bukan menggunakan rumus jumlah deret.

## Hasil Pengujian

| No. | Input                   | Keluaran yang Diharapkan              | Keluaran Aktual                          | Status   |
| --- | ----------------------- | ------------------------------------- | ---------------------------------------- | -------- |
| 1   | a = 2, d = 3, n = 5     | Suku: 2, 5, 8, 11, 14 dan jumlah = 40 | Suku: 2, 5, 8, 11, 14 dan jumlah = 40.00 | Berhasil |
| 2   | a = 10, d = -2, n = 4   | Suku: 10, 8, 6, 4 dan jumlah = 28     | Suku: 10, 8, 6, 4 dan jumlah = 28.00     | Berhasil |
| 3   | a = 1.5, d = 0.5, n = 3 | Suku: 1.5, 2.0, 2.5 dan jumlah = 6    | Suku: 1.5, 2.0, 2.5 dan jumlah = 6.00    | Berhasil |

### Contoh Hasil Pengujian 1

```text
Deret Aritmetika
Suku pertama a: 2
Beda d: 3
Banyak suku n: 5
Suku ke-1: 2.0
Suku ke-2: 5.0
Suku ke-3: 8.0
Suku ke-4: 11.0
Suku ke-5: 14.0
Jumlah deret: 40.00
```

### Contoh Hasil Pengujian 2

```text
Deret Aritmetika
Suku pertama a: 10
Beda d: -2
Banyak suku n: 4
Suku ke-1: 10.0
Suku ke-2: 8.0
Suku ke-3: 6.0
Suku ke-4: 4.0
Jumlah deret: 28.00
```

### Contoh Hasil Pengujian 3

```text
Deret Aritmetika
Suku pertama a: 1.5
Beda d: 0.5
Banyak suku n: 3
Suku ke-1: 1.5
Suku ke-2: 2.0
Suku ke-3: 2.5
Jumlah deret: 6.00
```

## Pengujian Program Latihan

Beberapa program latihan juga telah diuji melalui terminal.

### 1. Jumlah Bilangan

Input:

```text
n: 10
```

Output:

```text
Jumlah = 55
```

### 2. Validasi Input

Pengujian menggunakan nilai `-5` dan kemudian `75`.

Output:

```text
Nilai tidak valid.
Nilai 0-100: -5
Nilai 0-100: 75
Nilai diterima: 75.0
```

Program berhasil menolak nilai yang tidak valid dan menerima nilai dalam rentang 0–100.

### 3. Menghitung Bilangan Genap

Pengujian:

```text
n: 1
Jumlah bilangan genap: 0
```

```text
n: 2
Jumlah bilangan genap: 1
```

```text
n: 5
Jumlah bilangan genap: 2
```

Program berhasil menghitung jumlah bilangan genap dari 1 sampai `n`.

## Kesalahan yang Ditemukan

Saat menjalankan program `02_validasi_input.py`, sempat terjadi kesalahan karena perintah yang diketik tidak lengkap atau nama/path file tergabung.

Perintah yang benar adalah:

```bash
python latihan/02_validasi_input.py
```

Kesalahan tersebut diperbaiki dengan menuliskan nama file dan path secara benar.

## Refleksi

Dari latihan perulangan ini, saya belajar bahwa penulisan kondisi, batas perulangan, dan nama file harus diperhatikan dengan teliti. Kesalahan pada penulisan perintah dapat menyebabkan program tidak dapat dijalankan. Saya juga belajar bahwa perulangan dapat digunakan untuk menampilkan beberapa suku deret dan menghitung jumlahnya secara bertahap. Setelah diperbaiki, program dapat berjalan sesuai dengan hasil yang diharapkan.
