# Tugas 1 — Pengolahan Citra

Repository ini berisi implementasi beberapa fungsi dasar dalam pengolahan citra menggunakan Python, yaitu **downsampling**, **quantization**, dan perhitungan properti citra.

## Fungsi yang Diimplementasikan

### `downsample(image, n)`

Mengurangi resolusi citra dengan mengambil piksel pada interval `n`.

**Parameter:**

* `image` — citra yang akan diproses.
* `n` — interval pengambilan piksel.

### `quantize(image, k)`

Mengurangi jumlah level keabuan citra dari **256 level (8-bit)** menjadi `2^k` level.

Setelah proses quantization, nilai piksel dikembalikan ke rentang **0–255**.

**Parameter:**

* `image` — citra grayscale yang akan diproses.
* `k` — jumlah bit yang digunakan untuk merepresentasikan level keabuan.

### `image_properties(image, dpi, bit_depth=8)`

Menghitung beberapa properti dari citra, yaitu:

* **Dimensi fisik citra** (lebar × tinggi) dalam inci berdasarkan nilai DPI.
* **Ukuran memori citra** tanpa kompresi dalam KB.

**Parameter:**

* `image` — citra yang akan dianalisis.
* `dpi` — resolusi citra dalam dots per inch.
* `bit_depth` — kedalaman bit citra. Nilai default adalah `8`.

## Teknologi yang Digunakan

* Python
* NumPy
* Pillow
* Matplotlib
* Jupyter Notebook

## Cara Menjalankan

### 1. Clone Repository

Clone repository ini ke komputer lokal:

```bash
git clone <URL_REPOSITORY>
cd <NAMA_REPOSITORY>
```

### 2. Install Dependency

Install library yang dibutuhkan menggunakan `pip`:

```bash
pip install numpy pillow matplotlib
```

### 3. Buka Notebook

Buka file berikut menggunakan **Jupyter Notebook** atau **JupyterLab**:

```text
Tugas_1_103012400157.ipynb
```

### 4. Jalankan Program

Jalankan seluruh cell pada notebook secara berurutan untuk melihat hasil implementasi dan pengujian setiap fungsi.

## Contoh Gambar

Notebook menggunakan contoh gambar yang diambil langsung dari **URL** untuk keperluan pengujian fungsi pengolahan citra.

Gambar tersebut digunakan sebagai input untuk proses:

* Downsampling
* Quantization
* Perhitungan properti citra

## Struktur Repository

```text
.
├── Tugas_1_103012400157.ipynb
└── README.md
```
