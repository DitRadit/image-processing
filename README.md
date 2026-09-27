\## Fungsi yang Diimplementasikan



\### `downsample(image, n)`

Mengurangi resolusi citra dengan mengambil piksel pada interval `n`.



\### `quantize(image, k)`

Mengurangi jumlah level keabuan citra dari 256 (8-bit) menjadi `2^k` level, kemudian hasilnya di-scale kembali ke rentang \[0, 255].



\### `image\_properties(image, dpi, bit\_depth=8)`

Menghitung:

\- Dimensi fisik citra (lebar × tinggi) dalam inci, berdasarkan nilai DPI

\- Ukuran memori citra tanpa kompresi, dalam KB



\## Cara Menjalankan



1\. Clone repository ini

2\. Install dependency yang dibutuhkan:

```bash

&#x20;  pip install numpy pillow matplotlib

```

3\. Buka `Tugas\_1\_103012400157.ipynb` menggunakan Jupyter Notebook / JupyterLab

4\. Jalankan seluruh cell secara berurutan



\## Contoh Gambar



Notebook ini menggunakan contoh gambar yang diambil langsung dari URL untuk keperluan pengujian.

