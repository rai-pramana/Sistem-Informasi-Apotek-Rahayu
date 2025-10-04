# Sistem Informasi Apotek Rahayu

<div align="center">
  <h3>🏥 Aplikasi Manajemen Apotek Berbasis Console 🏥</h3>
  <p>Program untuk memfasilitasi kegiatan transaksi di apotek yang menyediakan berbagai pilihan obat dan layanan kesehatan</p>
</div>

---

## 📋 Informasi Project

| **Field**     | **Value**                                       |
| ------------- | ----------------------------------------------- |
| **Judul**     | Program Apotek Rahayu                           |
| **Deskripsi** | Program untuk memfasilitasi transaksi di apotek |
| **Developer** | I Kadek Rai Pramana (2105551094)                |
| **Tanggal**   | 28 Desember 2021                                |
| **Versi**     | 1.0                                             |
| **Bahasa**    | C Programming Language                          |
| **Platform**  | Windows Console Application                     |

---

## 🚀 Fitur Utama

### 👤 Untuk Pelanggan:

-   **🛒 Belanja Obat**: Beli obat dengan katalog lengkap (20+ jenis obat)
-   **🦠 Tes COVID-19**: Layanan tes kesehatan (GeNose, Rapid Test, PCR)
-   **🔍 Pencarian Obat**: Cari obat berdasarkan keluhan kesehatan
-   **💊 Info Khasiat**: Informasi lengkap khasiat seluruh obat
-   **👤 Profil Pengguna**: Kelola data profil pribadi
-   **📊 Riwayat Transaksi**: Lihat riwayat pembelian dan total pengeluaran

### 🔧 Untuk Admin:

-   **📈 Laporan Penjualan**: Analisa data transaksi dan penghasilan
-   **👥 Manajemen Pelanggan**: Kelola data pelanggan terdaftar
-   **🔍 Pencarian Data**: Cari data transaksi dan pelanggan
-   **🗑️ Manajemen Data**: Hapus data transaksi dan pelanggan
-   **📊 Dashboard Admin**: Statistik penjualan dan manajemen

### 🎯 Fitur Khusus:

-   **💰 Sistem PPN**: Pajak otomatis untuk pelanggan non-member
-   **🎫 Struk Digital**: Cetak struk transaksi otomatis
-   **📁 Penyimpanan File**: Data tersimpan dalam file eksternal
-   **🔐 Sistem Login**: Autentikasi user dan admin
-   **🎨 UI Console**: Interface yang user-friendly dengan ASCII art

---

## 🛠️ Teknologi yang Digunakan

-   **Language**: C Programming
-   **Compiler**: GCC atau Microsoft Visual C++
-   **IDE**: Code::Blocks / Dev-C++ / Visual Studio
-   **OS**: Windows
-   **Libraries**:
    -   `stdio.h` - Input/output operations
    -   `strings.h` - String manipulation
    -   `time.h` - Date and time functions

---

## 📁 Struktur File

```
Sistem-Informasi-Apotek-Rahayu/
├── main.c                    # File utama program
├── main.exe                  # Executable file
├── README.md                 # Dokumentasi project
├── data_pelanggan.txt        # Database pelanggan (auto-generated)
├── data_transaksi.txt        # Database transaksi (auto-generated)
└── screenshot/               # Screenshot aplikasi
    ├── Page_09_Image_0001.png
    ├── Page_10_Image_0001.png
    └── ... (35+ screenshot files)
```

---

## 💊 Katalog Obat

| No  | Nama Obat             | Harga      | Khasiat                       |
| --- | --------------------- | ---------- | ----------------------------- |
| 1   | HI-Stimuno 100 kapsul | Rp 80.000  | Meningkatkan daya tahan tubuh |
| 2   | Tolak Angin Cair      | Rp 35.000  | Meredakan masuk angin         |
| 3   | OB Herbal Sirup       | Rp 25.000  | Meredakan batuk               |
| 4   | HerbaCOLD             | Rp 130.000 | Meredakan flu                 |
| 5   | Bilon                 | Rp 100.000 | Menurunkan gula darah         |
| ... | _Dan 15 obat lainnya_ |            |                               |

## 🦠 Layanan Tes COVID-19

| No  | Jenis Tes           | Harga      | Deskripsi                         |
| --- | ------------------- | ---------- | --------------------------------- |
| 1   | GeNose C19          | Rp 30.000  | Tes cepat dengan teknologi GeNose |
| 2   | Rapid Test Antigen  | Rp 180.000 | Tes antigen untuk deteksi virus   |
| 3   | Rapid Test Antibodi | Rp 150.000 | Tes antibodi untuk imunitas       |
| 4   | Swab PCR            | Rp 900.000 | Tes PCR akurasi tinggi            |

---

## 🚀 Cara Instalasi & Penggunaan

### Instalasi:

1. **Clone Repository**

    ```bash
    git clone https://github.com/rai-pramana/Sistem-Informasi-Apotek-Rahayu.git
    cd Sistem-Informasi-Apotek-Rahayu
    ```

2. **Compile Program** (jika diperlukan)

    ```bash
    gcc main.c -o main.exe
    ```

3. **Jalankan Program**
    ```bash
    ./main.exe
    ```

### Penggunaan:

1. **Pilih Mode**: Pelanggan atau Admin
2. **Login/Register**: Daftar akun baru atau login dengan akun existing
3. **Navigasi Menu**: Gunakan angka untuk memilih menu
4. **Transaksi**: Ikuti instruksi untuk melakukan pembelian
5. **Logout**: Keluar dari sistem dengan aman

### Default Admin Login:

-   **Username**: `admin`
-   **Password**: `admin123`

---

## 📱 Screenshot Aplikasi

![Screenshot 1](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_09_Image_0001.png>)

![Screenshot 2](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_10_Image_0001.png>)

![Screenshot 3](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_10_Image_0002.png>)

![Screenshot 4](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_11_Image_0001.png>)

![Screenshot 5](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_12_Image_0001.png>)

![Screenshot 6](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_12_Image_0002.png>)

![Screenshot 7](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_13_Image_0001.png>)

![Screenshot 8](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_14_Image_0001.png>)

![Screenshot 9](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_15_Image_0001.png>)

![Screenshot 10](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_16_Image_0001.png>)

![Screenshot 11](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_17_Image_0001.png>)

![Screenshot 12](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_18_Image_0001.png>)

![Screenshot 13](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_19_Image_0001.png>)

![Screenshot 14](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_20_Image_0001.png>)

![Screenshot 15](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_21_Image_0001.png>)

![Screenshot 16](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_21_Image_0002.png>)

![Screenshot 17](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_22_Image_0001.png>)

![Screenshot 18](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_23_Image_0001.png>)

![Screenshot 19](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_24_Image_0001.png>)

![Screenshot 20](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_25_Image_0001.png>)

![Screenshot 21](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_26_Image_0001.png>)

![Screenshot 22](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_27_Image_0001.png>)

![Screenshot 23](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_28_Image_0001.png>)

![Screenshot 24](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_29_Image_0001.png>)

![Screenshot 25](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_30_Image_0001.png>)

![Screenshot 26](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_30_Image_0002.png>)

![Screenshot 27](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_31_Image_0001.png>)

![Screenshot 28](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_32_Image_0001.png>)

![Screenshot 29](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_33_Image_0001.png>)

![Screenshot 30](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_33_Image_0002.png>)

![Screenshot 31](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_34_Image_0001.png>)

![Screenshot 32](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_35_Image_0001.png>)

![Screenshot 33](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_35_Image_0002.png>)

![Screenshot 34](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_36_Image_0001.png>)

![Screenshot 35](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_37_Image_0001.png>)

![Screenshot 36](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_38_Image_0001.png>)

![Screenshot 37](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_38_Image_0002.png>)

![Screenshot 38](<screenshot/Laporan%20Pemrograman(D)_2105551094_I%20Kadek%20Rai%20Pramana_Page_39_Image_0001.png>)

---

## 🔧 Fungsi & Algoritma Utama

### 🔐 Sistem Autentikasi

-   Login pelanggan dan admin
-   Registrasi pelanggan baru
-   Validasi username dan password

### 💰 Sistem Transaksi

-   Perhitungan harga otomatis
-   Sistem PPN untuk non-member
-   Generate kode transaksi unik
-   Cetak struk digital

### 📊 Manajemen Data

-   CRUD operations untuk pelanggan
-   CRUD operations untuk transaksi
-   File-based database
-   Search dan filter data

### 🎯 Fitur Khusus

-   Pencarian obat berdasarkan keluhan
-   Sistem member dengan diskon PPN
-   Laporan keuangan real-time
-   ASCII art interface

---

## 💡 Keunggulan Program

1. **👥 User-Friendly**: Interface console yang mudah dipahami
2. **🔒 Secure**: Sistem login yang aman
3. **💾 Persistent**: Data tersimpan dalam file
4. **🎯 Complete**: Fitur lengkap untuk manajemen apotek
5. **🚀 Fast**: Performance tinggi untuk aplikasi console
6. **🔍 Smart Search**: Pencarian obat berdasarkan keluhan
7. **💰 Business Logic**: Sistem PPN dan member discount

---

## 🤝 Kontribusi

Jika Anda ingin berkontribusi pada project ini:

1. Fork repository
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

---

## 📞 Kontak Developer

**I Kadek Rai Pramana**

-   📧 Email: rai.pramana46@gmail.com

---

## 📜 Lisensi

Project ini dibuat untuk keperluan tugas besar mata kuliah Pemrograman Prosedural.

---

<div align="center">
  <p>⭐ Jika project ini membantu, berikan star di repository! ⭐</p>
  <p>🚀 Happy Coding! 🚀</p>
</div>
