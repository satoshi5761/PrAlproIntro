# PrAlproIntro – Pengenalan Pemrograman Alpro

Repository ini berisi tugas pengenalan pemrograman untuk mata kuliah Algoritma dan Pemrograman (Alpro / PrAlpro).

## Soal: Heronian Mean Menjadi Bilangan Bulat

**Heronian mean** (atau rata-rata Heronian) dari dua bilangan positif *a* dan *b* didefinisikan sebagai:

$$
H(a, b) = \frac{a + \sqrt{ab} + b}{3}
$$

**Tugas Anda:**

Cari bilangan bulat positif **terkecil** *b* dengan syarat **b > 40**, sehingga **H(40, b)** juga merupakan bilangan bulat positif (integer).

Contoh penggunaan `.is_integer()`:

```python
print(130.0.is_integer())   # True
print(17.333.is_integer())  # False
print(52.0.is_integer())    # True