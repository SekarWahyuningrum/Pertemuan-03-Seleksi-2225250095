# Pertemuan-03-Seleksi-2225250095
# Pertemuan 03 Seleksi Python

## Identitas

* **Nama:** Sekar Wahyuningrum
* **NIM:** 2225250095
* **Kelas:** 3E
* **Mata Kuliah:** Algoritma dan Pemrograman
* **Program Studi:** Pendidikan Matematika
* **Universitas:** Universitas Sultan Ageng Tirtayasa (UNTIRTA)

## Tujuan

Mempelajari dan menerapkan struktur seleksi dalam Python, meliputi `if`, `if-else`, kondisi majemuk, dan `nested if` untuk membuat program yang dapat mengambil keputusan berdasarkan kondisi tertentu.

## Cara Menjalankan

Program dapat dijalankan menggunakan perintah:

```bash
python3 tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas

1. Menampilkan judul program **Analisis Persamaan Kuadrat**.
2. Meminta pengguna memasukkan koefisien `a`, `b`, dan `c`.
3. Memeriksa nilai koefisien `a`.
4. Jika `a = 0`, maka program menampilkan bahwa input tersebut bukan persamaan kuadrat.
5. Jika `a` tidak sama dengan 0, program menghitung nilai diskriminan.
6. Jika diskriminan lebih besar dari 0, persamaan memiliki dua akar real yang berbeda.
7. Jika diskriminan sama dengan 0, persamaan memiliki satu akar real kembar.
8. Jika diskriminan kurang dari 0, persamaan tidak memiliki akar real.
9. Program menampilkan hasil analisis berdasarkan nilai diskriminan.

## Hasil Pengujian

| No. | Input (a, b, c) | Keluaran yang Diharapkan                              | Keluaran Aktual                                       | Status   |
| --- | --------------- | ----------------------------------------------------- | ----------------------------------------------------- | -------- |
| 1   | 1, -5, 6        | Diskriminan = 1.00 dan memiliki dua akar real berbeda | Diskriminan = 1.00 dan memiliki dua akar real berbeda | Berhasil |
| 2   | 1, -4, 4        | Diskriminan = 0.00 dan memiliki satu akar real kembar | Diskriminan = 0.00 dan memiliki satu akar real kembar | Berhasil |
| 3   | 1, 2, 5         | Diskriminan = -16.00 dan tidak memiliki akar real     | Diskriminan = -16.00 dan tidak memiliki akar real     | Berhasil |
| 4   | 0, 2, 1         | Bukan persamaan kuadrat                               | Bukan persamaan kuadrat                               | Berhasil |

## Refleksi

Kesalahan logika yang ditemukan adalah belum membedakan tiga kemungkinan nilai diskriminan, yaitu diskriminan positif, sama dengan nol, dan negatif. Kesalahan tersebut diperbaiki dengan menggunakan `if`, `elif`, dan `else` untuk memeriksa setiap kondisi. Setelah diperbaiki, program dapat menentukan jenis akar persamaan kuadrat dengan benar berdasarkan nilai diskriminan.

# 12 Kuis Formatif

**Pilih atau tuliskan jawaban paling tepat. Kerjakan tanpa menjalankan kode terlebih dahulu.**

### 1. Apa tipe hasil ekspresi `7 >= 5`?

**Jawaban:** `bool` (Boolean)

### 2. Operator apa yang digunakan untuk menguji kesamaan dua nilai?

**Jawaban:** `==`

### 3. Apa perbedaan utama `=` dan `==`?

**Jawaban:** `=` digunakan untuk memberikan atau menyimpan nilai ke dalam variabel, sedangkan `==` digunakan untuk membandingkan apakah dua nilai sama.

### 4. Jika aturan berbunyi minimal 75, apakah operator `> 75` sudah tepat? Jelaskan.

**Jawaban:** Tidak tepat, karena "minimal 75" berarti nilai 75 juga termasuk. Operator yang tepat adalah `>= 75`.

### 5. Kapan blok `else` dijalankan?

**Jawaban:** Blok `else` dijalankan ketika kondisi pada `if` atau kondisi sebelumnya bernilai salah (`False`).

### 6. Berapa sisa `14 % 2` dan keputusan apa yang dapat dibuat dari hasil itu?

**Jawaban:** Sisa `14 % 2` adalah `0`. Hal tersebut menunjukkan bahwa 14 merupakan bilangan genap.

### 7. Untuk syarat nilai minimal 60 dan hadir minimal 80, operator logika apa yang digunakan?

**Jawaban:** Operator `and`, karena kedua syarat harus terpenuhi.

### 8. Mengapa nested if sesuai ketika pertanyaan kedua hanya relevan setelah syarat pertama terpenuhi?

**Jawaban:** Karena `nested if` memungkinkan kondisi kedua diperiksa hanya setelah kondisi pertama terpenuhi, sehingga alur keputusan menjadi lebih terstruktur.

### 9. Sebutkan tiga input untuk menguji batas kelulusan 60.

**Jawaban:** Nilai `59`, `60`, dan `61`.

### 10. Perintah apa yang mengirim commit lokal ke remote setelah push pertama berhasil?

**Jawaban:**

```bash
git push
```
