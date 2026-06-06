# Flowchart Praktikum Python Literals & Operators

## Soal 1 - Membuat Fungsi Input dan Menampilkan ke Konsol

```mermaid
flowchart TD
    A([START])
    B[/Input: Masukkan nama anda/]
    C[Variabel nama menyimpan input]
    D[/Cetak: Halo nama/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```

---

## Soal 2 - Membuat Fungsi Input dengan Argumen

```mermaid
flowchart TD
    A([START])
    B[Passing Argumen nama = ihsan]
    C[/Cetak Halo ihsan/]
    D([END])

    A --> B
    B --> C
    C --> D
```

---

## Soal 3 - Memahami Hasil dari Fungsi Input

```mermaid
flowchart TD
    A([START])
    B[/Input Angka/]
    C[Cek Tipe Data]
    D[/Cetak Tipe String/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```

---

## Soal 4 - Mengkonversi Tipe Data Float

```mermaid
flowchart TD
    A([START])
    B[/Input Desimal/]
    C[Konversi ke Float]
    D[/Cetak Nilai Float/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```

---

## Soal 5 - Menghitung Sisi Miring Segitiga Dengan Variabel

```mermaid
flowchart TD
    A([START])
    B[/Input Sisi A dan Sisi B/]
    C[Hitung hypo = akar A kuadrat + B kuadrat]
    D[/Cetak Nilai Hypo/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```

---

## Soal 6 - Menghitung Sisi Miring Segitiga Tanpa Variabel

```mermaid
flowchart TD
    A([START])
    B[/Input Sisi A dan Sisi B/]
    C[Hitung Langsung Pythagoras]
    D[/Cetak Hasil Perhitungan/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```


## Soal 7 - Operator Konkatenasi

```mermaid
flowchart TD
    A([START])
    B[Set kata1 = Informatika]
    C[Set kata2 = UINSSC]
    D[Gabungkan kata1 + spasi + kata2]
    E[/Cetak Informatika UINSSC/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

## Soal 8 - Operator Replikasi

```mermaid
flowchart TD
    A([START])
    B[Replikasi string SOLID × 3]
    C[/Cetak SOLID SOLID SOLID/]
    D([END])

    A --> B
    B --> C
    C --> D
```

---

## Soal 9 - Konversi ke String

```mermaid
flowchart TD
    A([START])
    B[Hitung Luas]
    C[Konversi Menjadi String]
    D[Gabungkan Dengan Kalimat]
    E[/Cetak Pesan Pengumuman/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

## Soal 10 - Melihat Tipe Data dari Variabel

```mermaid
flowchart TD
    A([START])
    B[/Input Data/]
    C[Konversi Ke Float]
    D[/Cetak Tipe Awal String/]
    E[/Cetak Tipe Akhir Float/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

## Soal 11 - Kuis 7 Menu Pembatas

```mermaid
flowchart TD
    A([START])
    B[Buat Pembatas 20 Karakter]
    C[/Cetak Pembatas/]
    D[/Cetak MENU PRAKTIKUM/]
    E[/Cetak Pembatas/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

## Soal 12 - Kuis 8 String Method Upper

```mermaid
flowchart TD
    A([START])
    B[/Input Nama Mata Kuliah/]
    C[Ubah Menjadi Huruf Kapital]
    D[/Cetak Pesan Selamat/]
    E([END])

    A --> B
    B --> C
    C --> D
    D --> E
```


## Soal 13 - Kuis 9 Cek Bilangan Genap

```mermaid
flowchart TD
    A([START])
    B[/Input Angka/]
    C[Konversi ke Integer]
    D[Hitung angka % 2]
    E{Hasil == 0 ?}
    F[/Cetak True/]
    G[/Cetak False/]
    H([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E -- Ya --> F
    E -- Tidak --> G
    F --> H
    G --> H
```
