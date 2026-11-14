# Kemampuan Numerik

[← Kembali ke Menu Utama](index.md) | [Latihan Kuis Numerik →](numerik.quiz.md)

---

## 1. Operasi Aljabar dan Pecahan

### A. Sifat-Sifat Operasi Hitung Aljabar

1. **Komutatif**
   - $a + b = b + a$
   - $a \times b = b \times a$
2. **Asosiatif**
   - $(a + b) + c = a + (b + c)$
   - $(a \times b) \times c = a \times (b \times c)$
3. **Distributif**
   - Perkalian terhadap penjumlahan: $(a + b) \times c = (a \times c) + (b \times c)$
   - Perkalian terhadap pengurangan: $(a - b) \times c = (a \times c) - (b \times c)$
   - Pembagian terhadap penjumlahan: $(a + b) : c = (a : c) + (b : c)$
   - Pembagian terhadap pengurangan: $(a - b) : c = (a : c) - (b : c)$

### B. Macam-Macam Bilangan

- **Bilangan bulat:** Terdiri atas bilangan bulat positif, nol, dan bilangan bulat negatif. *(Contoh: $\dots, -1, 0, 1, \dots$)*
- **Bilangan asli:** Bilangan bulat positif yang diawali angka 1 sampai tak hingga. *(Contoh: $1, 2, 3, \dots$)*
- **Bilangan cacah:** Bilangan bulat positif yang diawali angka 0 sampai tak hingga. *(Contoh: $0, 1, 2, 3, \dots$)*
- **Bilangan rasional:** Bilangan yang dapat dinyatakan sebagai pembagian dua bilangan bulat ($\frac{a}{b}, b \neq 0$). *(Contoh: $\frac{1}{2}, \frac{1}{7}$)*
- **Bilangan irasional:** Bilangan yang tidak dapat dinyatakan dalam pembagian dua bilangan bulat. *(Contoh: $\sqrt{2}, \log 3$)*
- **Bilangan prima:** Bilangan asli lebih dari 1 yang hanya habis dibagi 1 dan bilangan itu sendiri. *(Contoh: $2, 3, 5, 7, 11, 13$)*
- **Bilangan riil:** Gabungan bilangan rasional dan irasional. *(Contoh: $\frac{1}{2}, \sqrt{2}, \log 5$)*

### C. Operasi Pecahan

Penyederhanaan pembilang dan penyebut memudahkan operasi aritmetika agar angka tidak terlalu besar namun tetap bernilai sama.

1. **Penjumlahan** *(penyebut harus sama, $c \neq 0$)*:
   $$\frac{a}{c} + \frac{b}{c} = \frac{a + b}{c}$$
2. **Pengurangan** *(penyebut harus sama, $c \neq 0$)*:
   $$\frac{a}{c} - \frac{b}{c} = \frac{a - b}{c}$$
3. **Perkalian**:
   $$\frac{a}{b} \times \frac{c}{d} = \frac{a \times c}{b \times d}$$
4. **Pembagian** *(kalikan dengan kebalikan pecahan kedua)*:
   $$\frac{a}{b} : \frac{c}{d} = \frac{a}{b} \times \frac{d}{c}$$

> **Trik Membandingkan Pecahan:** Jika selisih antara penyebut dan pembilang sama (misalnya $\frac{1}{2}$, $\frac{3}{4}$, $\frac{7}{8}$ yang semuanya berselisih $1$), maka pecahan dengan pembilang dan penyebut yang lebih besar memiliki nilai yang lebih besar.

---

## 2. Perbandingan

Perbandingan membandingkan dua nilai atau lebih dalam bentuk paling sederhana: $A : B = p : q$ atau $\frac{A}{B} = \frac{p}{q}$.

- **Mencari $A$ jika $B$ diketahui:**
  $$A = \frac{p}{q} \times B$$
- **Mencari nilai jika jumlah $(A + B)$ diketahui:**
  $$A = \frac{p}{p + q} \times (A + B)$$
- **Mencari nilai jika selisih $(A - B)$ diketahui:**
  $$A = \frac{p}{|p - q|} \times |A - B|$$

### Jenis Perbandingan

| Jenis Perbandingan | Ciri-Ciri | Rumus | Contoh Kasus |
| :--- | :--- | :--- | :--- |
| **Senilai (Lurus)** | Nilai awal naik, nilai akhir ikut naik | $\frac{A_1}{B_1} = \frac{A_2}{B_2}$ | Tinggi benda vs panjang bayangan |
| **Berbalik Nilai** | Nilai awal naik, nilai akhir turun | $A_1 \times B_1 = A_2 \times B_2$ | Jumlah pekerja vs waktu pengerjaan |
| **Bervariasi (3 Subjek)** | Gabungan senilai & berbalik nilai | $\frac{O_1}{S_1 \times t_1} = \frac{O_2}{S_2 \times t_2}$ | Objek ($O$), Subjek ($S$), Waktu ($t$) |

---

## 3. Barisan dan Deret

### A. Barisan dan Deret Aritmetika
Barisan dengan **selisih (beda)** antara dua suku berurutan yang selalu tetap ($b = U_n - U_{n-1}$).

- **Suku ke-$n$:** $U_n = a + (n - 1)b$
- **Jumlah $n$ suku pertama:** $S_n = \frac{n}{2}(2a + (n - 1)b) = \frac{n}{2}(a + U_n)$

### B. Barisan dan Deret Geometri
Barisan dengan **perbandingan (rasio)** antara dua suku berurutan yang selalu tetap ($r = \frac{U_n}{U_{n-1}}$).

- **Suku ke-$n$:** $U_n = a \cdot r^{n - 1}$
- **Deret geometri tak hingga** *(konvergen jika $-1 < r < 1$)*: $S_\infty = \frac{a}{1 - r}$

---

## 4. Persamaan dan Pertidaksamaan

### A. Persamaan Linear
1. **Persamaan Linear Satu Variabel (PLSV):** Bentuk umum $ax + b = 0$ ($a \neq 0$).
2. **Sistem Persamaan Linear Dua Variabel (SPLDV):** Bentuk umum $ax + by + c = 0$. Dapat diselesaikan dengan metode **Eliminasi**, **Substitusi**, atau **Campuran**.

### B. Pertidaksamaan Linear
Menggunakan tanda ketidaksamaan ($<, >, \le, \ge$).
- **Aturan penting:** Jika kedua ruas dikali atau dibagi dengan **bilangan negatif**, tanda pertidaksamaan **wajib dibalik** (misalnya $<$ menjadi $>$).

---

## 5. Geometri Dasar

### A. Garis dan Sudut
- **Hubungan Garis:** Sejajar ($//$), berpotongan, berhimpit, bersilangan (tidak sebidang dan tidak berpotongan), vertikal, dan horizontal.
- **Satuan Sudut:** $1^\circ = 60'$, $1' = 60''$, sehingga $1^\circ = 3.600''$.
- **Jenis Sudut:**
  - Lancip: $< 90^\circ$
  - Siku-siku: $90^\circ$
  - Tumpul: $> 90^\circ$ dan $< 180^\circ$
  - Lurus: $180^\circ$
  - Refleks: antara $180^\circ$ dan $360^\circ$
- **Hubungan Antarsudut:**
  - **Berpelurus (suplemen):** Jumlah kedua sudut $= 180^\circ$.
  - **Berpenyiku (komplemen):** Jumlah kedua sudut $= 90^\circ$.
  - **Bertolak belakang:** Besar kedua sudut sama.
  - **Dua garis sejajar dipotong garis lain:** Sudut sehadap, dalam berseberangan, dan luar berseberangan memiliki **besar yang sama**. Sudut dalam sepihak dan luar sepihak berjumlah **$180^\circ$**.

---

## 6. Aritmetika Sosial

### A. Untung, Rugi, dan Persentase
- **Untung:** $\text{Harga Jual} - \text{Harga Beli}$ *(jika harga jual > harga beli)*
- **Rugi:** $\text{Harga Beli} - \text{Harga Jual}$ *(jika harga beli > harga jual)*
- **Persentase Untung:** $\frac{\text{Untung}}{\text{Harga Beli}} \times 100\%$
- **Persentase Rugi:** $\frac{\text{Rugi}}{\text{Harga Beli}} \times 100\%$

### B. Rabat (Diskon), Bruto, Tara, dan Neto
- **Harga Bersih:** $\text{Harga Kotor} - \text{Rabat (Diskon)}$
- **Bruto (Berat Kotor):** $\text{Neto} + \text{Tara}$
- **Neto (Berat Bersih):** $\text{Bruto} - \text{Tara}$
- **Tara (Berat Kemasan):** $\text{Persen Tara} \times \text{Bruto}$

### C. Bunga Tabungan (Bunga Tunggal) dan Pajak
- **Bunga $1$ Tahun:** $\text{Persen Bunga} \times \text{Modal}$
- **Bunga $n$ Bulan:** $\frac{n}{12} \times \text{Persen Bunga} \times \text{Modal}$
- **Pajak Penghasilan (PPh):** $\text{Gaji Bersih} = \text{Gaji Kotor} - (\text{Persen PPh} \times \text{Penghasilan Kena Pajak})$