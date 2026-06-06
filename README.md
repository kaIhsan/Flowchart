# Flowchart Praktikum Python Pertemuan 2-7

# ([START]) dan ([END]) = Terminator
# [Proses] = Process
# [/Input atau Output/] = Input/Output
# {Kondisi} = Decision
# ((O)) = Connector

# -----------------
# Pertemuan 2
# -----------------

## Soal 1: Literal Integer (Positif & Negatif)

```mermaid
flowchart TD
    A([START]) --> B[/Cetak 11111111/]
    B --> C[/Cetak -11111111/]
    C --> D([END])
```

---

## Soal 2: Additional Convention (Octal & Hexadecimal)

```mermaid
flowchart TD
    A([START]) --> B[Konversi basis oktal\n0o123 ke desimal]
    B --> C[/Cetak 83/]
    C --> D[Konversi basis heksadesimal\n0x123 ke desimal]
    D --> E[/Cetak 291/]
    E --> F([END])
```

---

## Soal 3: Literal Float

```mermaid
flowchart TD
    A([START]) --> B[/Cetak 0.4/]
    B --> C[/Cetak 4.0/]
    C --> D[Interpretasi notasi singkat\n.4 menjadi 0.4]
    D --> E[/Cetak 0.4/]
    E --> F[Hitung eksponensial\n4e-1 sama dengan 4 x 10 pangkat -1]
    F --> G[/Cetak 0.4/]
    G --> H([END])
```

---

## Soal 4: Literal String

```mermaid
flowchart TD
    A([START]) --> B[/Cetak string dengan tanda kutip tunggal\nHasil: Halo Nanto/]
    B --> C[/Cetak string dengan tanda kutip ganda\nHasil: Halo Nanto/]
    C --> D([END])
```

---

## Soal 5: Boolean Values

```mermaid
flowchart TD
    A([START]) --> B[/Cetak True/]
    B --> C[/Cetak False/]
    C --> D{Evaluasi logika\nApakah 10 lebih besar dari 5?}
    D --> E[/Cetak True/]
    E --> F([END])
```

---

## Soal 6: Operator Pangkat

```mermaid
flowchart TD
    A([START]) --> B[Hitung 2 pangkat 3\nInteger dan Integer]
    B --> C[/Cetak 8/]
    C --> D[Hitung 2 pangkat 3.0\nInteger dan Float]
    D --> E[/Cetak 8.0/]
    E --> F[Hitung 2.0 pangkat 3\nFloat dan Integer]
    F --> G[/Cetak 8.0/]
    G --> H[Hitung 2.0 pangkat 3.0\nFloat dan Float]
    H --> I[/Cetak 8.0/]
    I --> J([END])
```

---

## Soal 7: Operator Perkalian

```mermaid
flowchart TD
    A([START]) --> B[Hitung 5 kali 2]
    B --> C[/Cetak 10/]
    C --> D[Hitung 5 kali 2.5]
    D --> E[/Cetak 12.5/]
    E --> F[Hitung 5.0 kali 2]
    F --> G[/Cetak 10.0/]
    G --> H[Hitung 5.0 kali 2.0]
    H --> I[/Cetak 10.0/]
    I --> J([END])
```

---

## Soal 8: Operator Pembagian

```mermaid
flowchart TD
    A([START]) --> B[Hitung 10 dibagi 2\nHasil otomatis dikonversi ke Float]
    B --> C[/Cetak 5.0/]
    C --> D[Hitung 10 dibagi 2.5]
    D --> E[/Cetak 4.0/]
    E --> F[Hitung 10.0 dibagi 2]
    F --> G[/Cetak 5.0/]
    G --> H[Hitung 10.0 dibagi 2.0]
    H --> I[/Cetak 5.0/]
    I --> J([END])
```

---

## Soal 9: Operator Floor Division

```mermaid
flowchart TD
    A([START]) --> B[Hitung 10 floor division 3\nHasil dibulatkan ke bawah]
    B --> C[/Cetak 3/]
    C --> D[Hitung 10 floor division 3.0]
    D --> E[/Cetak 3.0/]
    E --> F[Hitung 10.0 floor division 3]
    F --> G[/Cetak 3.0/]
    G --> H[Hitung 10.0 floor division 3.0]
    H --> I[/Cetak 3.0/]
    I --> J([END])
```

---

## Soal 10: Operator Modulo

```mermaid
flowchart TD
    A([START]) --> B[Hitung sisa bagi\n10 modulo 3]
    B --> C[/Cetak 1/]
    C --> D[Hitung sisa bagi\n10 modulo 3.0]
    D --> E[/Cetak 1.0/]
    E --> F[Hitung sisa bagi\n10.0 modulo 3]
    F --> G[/Cetak 1.0/]
    G --> H[Hitung sisa bagi\n10.0 modulo 3.0]
    H --> I[/Cetak 1.0/]
    I --> J([END])
```

---

## Soal 11: Operator Unary dan Binary

```mermaid
flowchart TD
    A([START]) --> B[Evaluasi unary negatif\ntanda minus pada literal 5]
    B --> C[/Cetak -5/]
    C --> D[Evaluasi unary positif\nmenegaskan posisi positif nilai 5]
    D --> E[/Cetak 5/]
    E --> F[Evaluasi binary\noperasi penjumlahan 5 plus 5]
    F --> G[/Cetak 10/]
    G --> H([END])
```

---

## Soal 12: Subekspresi

```mermaid
flowchart TD
    A([START]) --> B[Hitung perkalian\nhirarki: perkalian didahulukan\n3 kali 5 sama dengan 15]
    B --> C[Hitung penjumlahan\n2 tambah 15 sama dengan 17]
    C --> D[/Cetak 17/]
    D --> E[Hitung dalam kurung\nhirarki: kurung menginterupsi prioritas\n2 tambah 3 sama dengan 5]
    E --> F[Hitung perkalian luar\n5 kali 5 sama dengan 25]
    F --> G[/Cetak 25/]
    G --> H([END])
```

---

## Soal 13: Kuis - Hierarki Operator

```mermaid
flowchart TD
    A([START]) --> B[Prioritas 1 - Pangkat\nhirarki tertinggi\n2 pangkat 2 sama dengan 4]
    B --> C[Prioritas 2 - Perkalian\ndilanjutkan operasi perkalian\n3 kali 4 sama dengan 12]
    C --> D[Prioritas 3 - Penjumlahan\noperasi terakhir\n10 tambah 12 sama dengan 22]
    D --> E[/Cetak 22/]
    E --> F([END])
```

# -----------------
# Pertemuan 3
# -----------------

## Soal 1 & 2: Membuat dan Menggunakan Variabel

```mermaid
flowchart TD
    A([START]) --> B[Inisialisasi variabel\nvar = 3\nnilai = 90\nnama = Budi]
    B --> C[/Tampilkan var, nilai, nama\nOutput: 3, 90, Budi/]
    C --> D([END])
```

---

## Soal 3 & 4: Memasukkan Nilai Baru - Re-assignment

```mermaid
flowchart TD
    A([START]) --> B[Set tabungan = 500000]
    B --> C[/Tampilkan tabungan\nOutput: 500000/]
    C --> D[Update nilai baru\ntabungan = 750000]
    D --> E[/Tampilkan tabungan\nOutput: 750000/]
    E --> F([END])
```

---

## Soal 5: Shortcut Operators

```mermaid
flowchart TD
    A([START]) --> B[Inisialisasi\njumlah = 10]
    B --> C[Update dengan shortcut tambah\njumlah = 10 tambah 5\nsingkatan: jumlah plus-sama-dengan 5\nHasil: jumlah = 15]
    C --> D[Update dengan shortcut kali\njumlah = 15 kali 2\nsingkatan: jumlah kali-sama-dengan 2\nHasil: jumlah = 30]
    D --> E[/Tampilkan jumlah\nOutput: 30/]
    E --> F([END])
```

---

## Soal 6: Solving Simple Mathematical Problem

```mermaid
flowchart TD
    A([START]) --> B[Set panjang = 10\nSet lebar = 5]
    B --> C[Hitung luas\nluas = panjang kali lebar\nluas = 10 kali 5]
    C --> D[/Tampilkan luas\nOutput: 50/]
    D --> E([END])
```

---

## Soal 7: Kuis 3 - Menukar Nilai - Swapping

```mermaid
flowchart TD
    A([START]) --> B[Set a = 5\nSet b = 10]
    B --> C[Tukar posisi secara simultan\na dan b = b dan a]
    C --> D[/Tampilkan a dan b\nOutput: a = 10, b = 5/]
    D --> E([END])
```

---

## Soal 8 & 9: Kuis 4 & 5 - Eksponen dan Modulo

```mermaid
flowchart TD
    A([START]) --> B[Inisialisasi data\nangka = 2\npangkat = 3\nbil = 17\npembagi = 4]
    B --> C[Hitung eksponen\nhasil = 2 pangkat 3\nhasil = 8]
    C --> D[Hitung modulo\nsisa = 17 modulo 4\nsisa = 1]
    D --> E[/Tampilkan hasil dan sisa\nOutput: 8 dan 1/]
    E --> F([END])
```

# -----------------
# Pertemuan 4
# -----------------

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
# -----------------
# Pertemuan 5
# -----------------

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

# -----------------
# Pertemuan 6
# -----------------

# Soal 1 - Perulangan While Contoh 1
```mermaid
flowchart TD
    A([START])
    B[Set Counter 1 dan Limit 5]
    C{Counter Kurang Sama Dengan Limit}
    D[/Tampilkan Iterasi/]
    E[Counter Ditambah 1]
    F([END])

    A --> B
    B --> C
    C -- Ya --> D
    D --> E
    E --> C
    C -- Tidak --> F
```
# Soal 2 - Perulangan While Contoh 2
```mermaid
flowchart TD
    A([START])
    B[Set Stok 5]
    C{Stok Lebih Dari Nol}
    D[/Tampilkan Sisa Stok/]
    E[Kurangi Stok Satu]
    F[/Tampilkan Stok Habis/]
    G([END])

    A --> B
    B --> C
    C -- Ya --> D
    D --> E
    E --> C
    C -- Tidak --> F
    F --> G
```
# Soal 3 - Kasus Ganjil Genap Dengan While
```mermaid
flowchart TD
    A([START])
    B[Set Limit 20 dan N 1]
    C{N Kurang Sama Dengan Limit}
    D{N Modulo 2 Sama Dengan Nol}
    E[Masukkan Ke Daftar Genap]
    F[Masukkan Ke Daftar Ganjil]
    G[N Ditambah 1]
    H[/Tampilkan Rekapitulasi/]
    I([END])

    A --> B
    B --> C
    C -- Ya --> D
    D -- Ya --> E
    D -- Tidak --> F
    E --> G
    F --> G
    G --> C
    C -- Tidak --> H
    H --> I
```
# Soal 4 - Validasi Password Dengan While
```mermaid
flowchart TD
    A([START])
    B[Password Kosong]
    C{Password Benar}
    D[/Input Password/]
    E[/Tampilkan Akses Diterima/]
    F([END])

    A --> B
    B --> C
    C -- Tidak --> D
    D --> C
    C -- Ya --> E
    E --> F
```
# Soal 5 - Perulangan For Perbandingan Karakter
```mermaid
flowchart TD
    A([START])
    B[Ambil Pasangan Karakter]
    C{Karakter Lebih Kecil}
    D[Status Lebih Kecil]
    E{Karakter Lebih Besar}
    F[Status Lebih Besar]
    G[Status Sama]
    H((O))
    I[/Tampilkan Hasil/]
    J([END])

    A --> B
    B --> C
    C -- Ya --> D
    C -- Tidak --> E
    E -- Ya --> F
    E -- Tidak --> G
    D --> H
    F --> H
    G --> H
    H --> I
    I --> B
    B --> J
```
# Soal 6 - Perulangan For Eksponensial Dua
```mermaid
flowchart TD
    A([START])
    B[Set Batas Atas dan Dictionary]
    C[/Tampilkan Header Tabel/]
    D{Ambil Nilai I}
    E[Hitung Dua Pangkat I]
    F[/Tampilkan Baris Tabel/]
    G([END])

    A --> B
    B --> C
    C --> D
    D -- Ya --> E
    E --> F
    F --> D
    D -- Tidak --> G
```
# Soal 7 - Break Dan Continue Nested Loop
```mermaid
flowchart TD
    A([START])
    B{Loop Luar}
    C{Loop Dalam}
    D{I Sama Dengan J}
    E((Continue))
    F{I Tambah J Lebih Dari Empat}
    G((Break))
    H[/Tampilkan Koordinat/]
    I([END])

    A --> B
    B -- Ya --> C
    B -- Tidak --> I

    C -- Ya --> D
    C -- Tidak --> B

    D -- Ya --> E
    E --> C

    D -- Tidak --> F

    F -- Ya --> G
    G --> B

    F -- Tidak --> H
    H --> C
```
# Soal 8 - Implementasi Break
```mermaid
flowchart TD
    A([START])
    B[Set Target 120]
    C{Ambil Nilai I}
    D{Target Habis Dibagi I}
    E[/Tampilkan Pembagi/]
    F([END])

    A --> B
    B --> C
    C -- Ya --> D
    C -- Tidak --> F
    D -- Ya --> E
    E --> F
    D -- Tidak --> C
```
# Soal 9 - Implementasi Continue
```mermaid
flowchart TD
    A([START])
    B[Set Data Transaksi]
    C{Ambil Nilai}
    D{Nilai Kurang Sama Dengan Nol}
    E((Continue))
    F[Tambahkan Ke Total]
    G[/Tampilkan Transaksi/]
    H[/Tampilkan Pendapatan Bersih/]
    I([END])

    A --> B
    B --> C
    C -- Ya --> D
    C -- Tidak --> H

    D -- Ya --> E
    E --> C

    D -- Tidak --> F
    F --> G
    G --> C

    H --> I
```
# Soal 10 - While Dengan Else
```mermaid
flowchart TD
    A([START])
    B[Set N Sama Dengan Satu]
    C{N Kurang Sama Dengan Lima}
    D[/Tampilkan Nilai N/]
    E[N Ditambah Satu]
    F[/Loop Selesai Normal/]
    G([END])

    A --> B
    B --> C
    C -- Ya --> D
    D --> E
    E --> C
    C -- Tidak --> F
    F --> G
```
# Soal 11 - For Else Cek Bilangan Prima
```mermaid
flowchart TD
    A([START])
    B{Ambil Angka}
    C{Ada Pembagi}
    D[/Bukan Prima/]
    E[/Prima/]
    F((Break))
    G([END])

    A --> B
    B -- Ya --> C
    B -- Tidak --> G

    C -- Ya --> D
    D --> F
    F --> B

    C -- Tidak --> E
    E --> B
```
# Soal 12 - Ekspresi Logika Python
```mermaid
flowchart TD
    A([START])
    B[Set Variabel Logika]
    C[Evaluasi And]
    D[Evaluasi Or]
    E[Evaluasi Not]
    F[Evaluasi Perbandingan]
    G[/Tampilkan Semua Hasil/]
    H([END])

    A --> B --> C --> D --> E --> F --> G --> H
```
# Soal 13 - Logical Dan Bitwise
```mermaid
flowchart TD
    A([START])
    B[Set A dan B]
    C[Evaluasi Logical]
    D[Evaluasi Bitwise]
    E[/Tampilkan Hasil/]
    F([END])

    A --> B --> C --> D --> E --> F
```
# Soal 14 - Binary Shifting
```mermaid
flowchart TD
    A([START])
    B[Set Angka Dua Puluh]
    C[Geser Kiri Tiga Bit]
    D[Geser Kanan Dua Bit]
    E[/Tampilkan Desimal Dan Biner/]
    F([END])

    A --> B --> C --> D --> E --> F
```
# Soal 15 - Bitwise Masking Dan Encryption
```mermaid
flowchart TD
    A([START])
    B[Set Data Sensor Masker Dan Kunci]
    C[Ambil Empat Bit Terakhir]
    D[Enkripsi Dengan Shift Dan XOR]
    E[/Tampilkan Hasil/]
    F([END])

    A --> B --> C --> D --> E --> F
```

# -----------------
# Pertemuan 7
# -----------------

# Soal 1, 2, dan 5 - Konsep Indexing Positif dan Negatif

```mermaid
flowchart TD
    A([START])
    B[Inisialisasi List Buah]
    C[Akses Elemen Pertama]
    D[Akses Elemen Terakhir]
    E[/Tampilkan Hasil Indexing/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

# Soal 4 - Menghapus Elemen Del dan Remove

```mermaid
flowchart TD
    A([START])
    B[Inisialisasi List Angka]
    C[Hapus Elemen Pada Indeks 1]
    D[Hapus Nilai 3]
    E[/Tampilkan List Akhir/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

# Soal 7, 8, dan 9 - Menambah Elemen Append dan Insert

```mermaid
flowchart TD
    A([START])
    B[List Kosong]
    C{Masih Ada Iterasi}
    D{Metode Penambahan}
    E[Tambah Di Akhir]
    F[Sisip Di Depan]
    G[/Tampilkan Isi List/]
    H([END])

    A --> B
    B --> C

    C -- Ya --> D
    C -- Tidak --> G

    D -- Append --> E
    D -- Insert --> F

    E --> C
    F --> C

    G --> H
```

---

# Soal 10 dan 11 - Iterasi List

```mermaid
flowchart TD
    A([START])
    B{Mode Iterasi}
    C[Berdasarkan Indeks]
    D[Berdasarkan Nilai]
    E[Gunakan Range Dan Len]
    F[Gunakan For Item]
    G[/Cetak Indeks Dan Nilai/]
    H[/Cetak Isi List/]
    I((O))
    J([END])

    A --> B

    B -- Indeks --> C
    B -- Nilai --> D

    C --> E
    D --> F

    E --> G
    F --> H

    G --> I
    H --> I

    I --> J
```

---

# Soal 12 - Teknik Swap Menukar Nilai

```mermaid
flowchart TD
    A([START])
    B[Inisialisasi List]
    C[Ambil Elemen Pertama Dan Terakhir]
    D[Tukar Posisi Kedua Elemen]
    E[/Tampilkan List Baru/]
    F([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```

---

# Soal 13 - Kuis 20 Kompleksitas List

```mermaid
flowchart TD
    A([START])
    B[Inisialisasi List Kosong]
    C[Append Empat Data]
    D[Append Tujuh Data Dengan Loop]
    E[Hapus Beberapa Data]
    F[Sisipkan Data Baru]
    G[/Cetak Panjang Dan Isi List/]
    H([END])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
```
