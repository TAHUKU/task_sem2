# 🔍 Analisis Algoritma SEARCHING dan SORTING Berbasis Web

Aplikasi web interaktif berbasis **Streamlit** untuk mendemonstrasikan dan menganalisis performa algoritma pencarian (*Searching*) dan pengurutan (*Sorting*) pada studi kasus inventaris data gudang digital.  

Dibuat untuk memenuhi tugas/proyek analisis struktur data dan algoritma.

---

## ✨ Fitur Utama

1. **Multi-Algoritma Pencarian:**
   - 🔍 **Linear Search ($O(n)$):** Pencarian sekuensial murni yang aman untuk segala kondisi data.
   - 📚 **Binary Search ($O(\log n)$):** Pencarian bagi-dua yang cepat dengan pengamanan data kembar (*duplication-safe*).
   - ⚡ **Interpolation Search ($O(\log \log n)$):** Pencarian estimasi posisi berbasis rumus interpolasi nilai numerik.
2. **Pengurutan Data Gudang (Sorting):** Mendukung berbagai opsi susunan rak mulai dari acak, urut harga termurah/termahal, hingga pengurutan kategori ganda.
3. **Simulasi "Main Belakang" Pintar:** Sistem otomatis menyelaraskan data di memori latar belakang apabila algoritma berbasis *binary/interpolation* dijalankan pada data rak yang masih acak, lengkap dengan peringatan ilmiah.
4. **Metrik Kinerja Real-Time:** Menampilkan posisi indeks array komputer, jumlah langkah komputasi, dan waktu eksekusi presisi milidetik (`ms`).
5. **Perbandingan Simultan:** Fitur uji coba komparasi kecepatan ketiga algoritma secara bersamaan.

---

## 🛠️ Teknologi yang Digunakan
- **Python** (Bahasa Pemrograman utama)
- **Streamlit** (Framework antarmuka web interaktif)
- **Pandas** (Pengolahan dan visualisasi tabel data)
- **Random & Math** (Generator data tiruan dan kalkulasi matematis)

---

## 🚀 Cara Menjalankan Program Secara Lokal

Ikuti langkah-langkah berikut untuk menjalankan aplikasi di komputer Anda:

1. **Clone repository ini dan masuk ke direktori:**
   ```bash
   git clone [https://github.com/TAHUKU/task_sem2.git](https://github.com/TAHUKU/task_sem2.git)
   cd task_sem2
   
2. **Aktivkan environemnt**
  ```bash
  python -m venv venv
  source venv/bin/activate  # Untuk Windows gunakan: venv\Scripts\activate
  ```

3. **Install library yang dibutuhkan**
   ```bash
   pip install streamlit pandas
   ```
4. Jalankan aplikasi**
   ```bash
   streamlit tugas.py
   ```

## 👤 Pembuat
- **Nama:** Muhammad Hakkul Qoul
- **NIM:** 202569040005
- **AI Agent:** Gemini
- *Hakkul IT — 2026*
