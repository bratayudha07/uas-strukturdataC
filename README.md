# ⚡ Benchmarking Performa Struktur Data

## 📖 Deskripsi

Proyek ini merupakan tugas UAS Mata Kuliah Struktur Data yang bertujuan untuk membandingkan performa beberapa struktur data dalam operasi **Search**, **Insert**, dan **Delete**.

Aplikasi dibangun menggunakan **Streamlit** sehingga pengguna dapat melakukan benchmarking secara interaktif dan melihat hasilnya dalam bentuk tabel serta grafik.

---

## 🎯 Struktur Data yang Diuji

- Array/List
- Binary Search Tree (BST)
- Hash Table
- AVL Tree

---

## ✨ Fitur

- Generate dataset otomatis
- Pilihan ukuran dataset:
  - 100 data
  - 1.000 data
  - 10.000 data
- Pilihan jenis dataset:
  - Acak
  - Terurut
  - Descending
- Benchmark operasi:
  - Search
  - Insert
  - Delete
- Visualisasi hasil benchmark dalam bentuk tabel dan grafik
- Analisis performa otomatis
- Tabel kompleksitas algoritma

---

## 🛠️ Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- Random
- Time (`time.perf_counter()`)

---

## 📂 Struktur Project

```text
.
├── app.py
├── benchmark.py
├── README.md
└── requirements.txt
```

### app.py

Berisi antarmuka pengguna menggunakan Streamlit, meliputi:

- Generate dataset
- Pemilihan operasi benchmark
- Menjalankan benchmark
- Menampilkan tabel hasil
- Menampilkan grafik hasil
- Menampilkan analisis performa

### benchmark.py

Berisi logika utama benchmarking, meliputi:

- Pembuatan dataset
- Implementasi struktur data
- Operasi Search
- Operasi Insert
- Operasi Delete
- Pengukuran waktu eksekusi

---

## 🚀 Cara Menjalankan Program

### 1. Clone Repository

```bash
git clone https://github.com/username/nama-repository.git
cd nama-repository
```

### 2. Install Dependency

```bash
pip install -r requirements.txt
```

### 3. Jalankan Aplikasi

```bash
streamlit run app.py
```

---

## 📊 Kompleksitas Algoritma

| Struktur Data | Search | Insert | Delete |
|--------------|---------|---------|---------|
| Array/List | O(n) | O(1) | O(n) |
| BST | O(log n)* | O(log n)* | O(log n)* |
| Hash Table | O(1) | O(1) | O(1) |
| AVL Tree | O(log n) | O(log n) | O(log n) |

> **Catatan:** BST dapat mengalami penurunan performa menjadi O(n) apabila pohon tidak seimbang.

---

## 🎯 Tujuan Proyek

- Memahami implementasi struktur data.
- Membandingkan performa beberapa struktur data.
- Menganalisis pengaruh ukuran dan jenis dataset terhadap waktu eksekusi.
- Membandingkan hasil eksperimen dengan teori kompleksitas algoritma.

---

## 📈 Hasil yang Diharapkan

Melalui aplikasi ini, pengguna dapat memahami kelebihan dan kekurangan masing-masing struktur data serta mengetahui struktur data yang paling sesuai untuk kebutuhan tertentu berdasarkan hasil benchmarking.

---

## 👥 Kelompok 4

**Mata Kuliah:** Struktur Data  
**Program Studi:** Informatika  
**Universitas:** UIN Siber Syekh Nurjati Cirebon

### Anggota Kelompok

| Nama | NIM |
|--------|--------|
| Robbi Hamdi | 2530801057 |
| Azhalia Mozaik | 2530801059 |
| Much. Mentari Adriansyah | 2530801073 |
| Wafah Khonia | 253080105981 |

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik dalam memenuhi tugas UAS Mata Kuliah Struktur Data.

---

© 2026 Kelompok 4 – UAS Struktur Data, UIN Siber Syekh Nurjati Cirebon

## Kontributor

<table align="center">
  <tr>
    <td align="center" width="150">
      <a href="https://github.com/MuchmenAdrians">
        <img src="https://github.com/MuchmenAdrians.png" width="80" alt="Foto Much. Mentari Adriansyah"/><br />
        <sub><b>Much. Mentari Adriansyah</b></sub>
      </a>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/AzhaliaMozaik">
        <img src="https://github.com/AzhaliaMozaik.png" width="80" alt="Foto Azhalia Mozaik"/><br />
        <sub><b>Azhalia Mozaik</b></sub>
      </a>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/bratayudha07">
        <img src="https://github.com/bratayudha07.png" width="80" alt="Foto Robbi Hamdi"/><br />
        <sub><b>Robbi Hamdi</b></sub>
      </a>
    </td>
    <td align="center" width="150">
      <a href="https://github.com/khoniawafah-crypto">
        <img src="https://github.com/khoniawafah-crypto.png" width="80" alt="Foto Wafah Khonia"/><br />
        <sub><b>Wafah Khonia</b></sub>
      </a>
    </td>
  </tr>
</table>
