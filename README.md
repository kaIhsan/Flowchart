# Flowchart Praktikum Python 
# Pertemuan 4

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
#--------------------------------------------#
# Pertemuan 5
#--------------------------------------------#

# Soal 1 - Comparison Operator

```mermaid
flowchart TD
    A([START])
    B[Set a = 15 dan b = 20]
    C[Evaluasi a lebih besar dari b]
    D[Evaluasi a sama dengan b]
    E[Evaluasi a tidak sama dengan b]
    F[/Output False False True/]
    G([END])

    A --> B --> C --> D --> E --> F --> G
```

---

# Soal 2 - Kuis 11 Cek KKM

```mermaid
flowchart TD
    A([START])
    B[Set nilai = 90]
    C[Set kkm = 75]
    D[Evaluasi nilai lebih besar sama dengan kkm]
    E[/Output True/]
    F([END])

    A --> B --> C --> D --> E --> F
```

---

# Soal 3 - Conditional Statement If Tunggal

```mermaid
flowchart TD
    A([START])
    B[Status Kuliah Aktif]
    C{Status Aktif}
    D[/Tampilkan Mahasiswa Diperbolehkan/]
    E((O))
    F([END])

    A --> B --> C
    C -- Ya --> D
    C -- Tidak --> E
    D --> E
    E --> F
```

---

# Soal 4 - Conditional Statement Rangkaian If Mandiri

```mermaid
flowchart TD
    A([START])
    B[Set Stok = 5]
    C{Stok Lebih Dari 0}
    D[/Tampilkan Tersedia/]
    E((O))
    F{Stok Kurang Dari 10}
    G[/Tampilkan Hampir Habis/]
    H((O))
    I([END])

    A --> B --> C
    C -- Ya --> D
    C -- Tidak --> E
    D --> E
    E --> F
    F -- Ya --> G
    F -- Tidak --> H
    G --> H
    H --> I
```

---

# Soal 5 - Conditional Statement If Else

```mermaid
flowchart TD
    A([START])
    B[Set Nilai Akhir 65]
    C{Nilai Minimal 70}
    D[/Status Lulus/]
    E[/Status Remedial/]
    F((O))
    G([END])

    A --> B --> C
    C -- Ya --> D
    C -- Tidak --> E
    D --> F
    E --> F
    F --> G
```

---

# Soal 6 - Conditional Statement If Elif Else

```mermaid
flowchart TD
    A([START])
    B[Set Umur 20]
    C{Umur Kurang Dari 13}
    D[/Kategori Anak Anak/]
    E{Umur Kurang Dari 20}
    F[/Kategori Remaja/]
    G[/Kategori Dewasa/]
    H((O))
    I([END])

    A --> B --> C
    C -- Ya --> D
    C -- Tidak --> E
    D --> H
    E -- Ya --> F
    E -- Tidak --> G
    F --> H
    G --> H
    H --> I
```

---

# Soal 7 - Membandingkan Dua Angka Input

```mermaid
flowchart TD
    A([START])
    B[/Input X dan Y/]
    C[Konversi Ke Integer]
    D{X Lebih Besar Dari Y}
    E[/X Lebih Besar/]
    F{X Lebih Kecil Dari Y}
    G[/Y Lebih Besar/]
    H[/X Dan Y Sama/]
    I((O))
    J([END])

    A --> B --> C --> D
    D -- Ya --> E
    D -- Tidak --> F
    E --> I
    F -- Ya --> G
    F -- Tidak --> H
    G --> I
    H --> I
    I --> J
```

---

# Soal 8 - Kuis 12 Cek Ganjil Genap

```mermaid
flowchart TD
    A([START])
    B[/Input Angka N/]
    C[Konversi Ke Integer]
    D{Sisa Bagi Dua Sama Dengan Nol}
    E[/Angka Genap/]
    F[/Angka Ganjil/]
    G((O))
    H([END])

    A --> B --> C --> D
    D -- Ya --> E
    D -- Tidak --> F
    E --> G
    F --> G
    G --> H
```

---

# Soal 9 - Fungsi Max Dengan Variabel

```mermaid
flowchart TD
    A([START])
    B[Set Nilai Fisika Kimia Dan Biologi]
    C[Proses Fungsi Max]
    D[Simpan Ke Skor Terbaik]
    E[/Tampilkan Skor Terbaik/]
    F([END])

    A --> B --> C --> D --> E --> F
```

---

# Soal 10 - Fungsi Max Pada List

```mermaid
flowchart TD
    A([START])
    B[Set Data Kecepatan]
    C[Cari Nilai Terbesar Dalam List]
    D[/Tampilkan List Kecepatan/]
    E[/Tampilkan Nilai Maksimum/]
    F([END])

    A --> B --> C --> D --> E --> F
```

