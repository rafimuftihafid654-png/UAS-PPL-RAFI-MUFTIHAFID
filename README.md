# UAS-PPL-RAFI-MUFTIHAFID
Repository untuk laporan UAS Praktikum Pengujian Perangkat Lunak
📋 Cakupan Pengujian (Test Scope)
Proyek ini mengotomasi 12 Test Case yang dikelompokkan ke dalam 4 modul utama sesuai dengan rencana pengujian manual:

Modul 1: User Authentication (Login Valid, Login Gagal, & Logout).
Modul 2: Product Catalog (Filter Kategori, Navigasi Next, & Detail Produk).
Modul 3: Shopping Cart (Tambah Produk, Lihat Keranjang, & Hapus Produk).
Modul 4: Purchase Flow (Checkout Valid, Form Kosong, & Validasi Keranjang Kosong).
🛠️ Arsitektur & Teknologi
Proyek ini dibangun dengan standar industri pengujian perangkat lunak:

Bahasa Pemrograman: Java 17.
Automation Tool: Selenium WebDriver (Manager).
Test Runner: TestNG (untuk manajemen urutan tes dan assertions).
Reporting: ExtentReports (menghasilkan laporan HTML interaktif).
Design Pattern: Page Object Model (POM) untuk memisahkan logika UI dan skrip tes.
RafiOtomatisasiTesting/
├── reports/                 # Laporan hasil eksekusi (HTML)
├── src/
│   ├── main/java/           # Page Objects (Struktur Elemen Web)
│   └── test/java/           # Test Suites (Logika Pengujian)
├── pom.xml                  # Konfigurasi Dependensi Maven
└── testng.xml               # Pengatur Eksekusi Seluruh Modul
🚀 Cara Menjalankan (Installation & Execution)
Clone repositori ini:
git clone https://github.com/UsernameAnda/RafiOtomatisasiTesting.git
Buka proyek menggunakan IntelliJ IDEA atau Eclipse.
Pastikan koneksi internet aktif untuk mengunduh dependensi Maven.
Klik kanan pada file testng.xml di root folder.
Pilih "Run 'testng.xml'".
Setelah eksekusi selesai, buka folder reports/TestReport.html menggunakan browser pilihan Anda.
🐛 Bug Discovery (BUG-001)
Berdasarkan hasil pengujian otomatis, sistem berhasil mendeteksi satu bug fungsional kritis:

ID: BUG-001.
Deskripsi: Tombol "Place Order" tetap aktif meskipun keranjang belanja kosong.
Status Otomasi: FAILED (Sesuai dengan temuan pada pengujian manual).
👤 Identitas Penguji
Nama: Rafi muftihafid.
NPM: 230209087.
Mata Kuliah: Praktikum Perangkat Lunak (UAS).
Cara Menggunakan:
Buat file baru di root project IntelliJ Anda dengan nama README.md.
Salin dan tempel (copy-paste) teks di atas.
Simpan dan lakukan Commit & Push ke GitHub.
Tampilan di GitHub akan otomatis menjadi rapi dengan ikon dan tabel.
