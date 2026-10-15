# Pertemuan 07 Fungsi Python

**Nama:** Sasa Nursaadah

**NIM:** 2225250130

**Kelas:** 3F

## Tujuan

Mempelajari penggunaan fungsi, parameter, nilai kembali (*return value*), dan *scope* untuk membuat program Python yang modular.

## Cara Menjalankan

Jalankan program utama dengan perintah berikut melalui terminal:

```bash
python praktik/utilitas_matematika.py
```

## Struktur Fungsi

Program `utilitas_matematika.py` memiliki beberapa fungsi berikut:

1. `luas_persegi_panjang(p, l)` digunakan untuk menghitung luas persegi panjang berdasarkan panjang dan lebar.
2. `luas_segitiga(a, t)` digunakan untuk menghitung luas segitiga berdasarkan alas dan tinggi.
3. `jumlah_n(n)` digunakan untuk menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan.
4. `faktorial(n)` digunakan untuk menghitung faktorial bilangan n.
5. `tampilkan_menu()` digunakan untuk menampilkan pilihan operasi yang tersedia pada program.

## Hasil Pengujian

| Operasi              | Input                  | Hasil yang Diharapkan |
| -------------------- | ---------------------- | --------------------- |
| Luas persegi panjang | Panjang = 8, lebar = 5 | 40.0                  |
| Luas segitiga        | Alas = 10, tinggi = 6  | 30.0                  |
| Jumlah 1 sampai n    | n = 10                 | 55                    |
| Faktorial            | n = 5                  | 120                   |
| Faktorial            | n = 0                  | 1                     |

## Refleksi

Dengan menggunakan fungsi, program menjadi lebih terstruktur karena setiap fungsi memiliki tugas masing-masing. Kode juga dapat digunakan kembali tanpa harus menulis ulang proses perhitungan, sehingga program lebih mudah dipahami dan dikembangkan.