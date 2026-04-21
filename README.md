# Asa Weekly Expense Analyst
---
Repositori ini berisi file export JSON untuk workflow n8n yang berfungsi sebagai asisten keuangan mingguan otomatis.

## 🌟 Fitur Utama
- **Otomasi Penjadwalan:** Berjalan setiap Minggu pagi menggunakan Schedule Trigger.
- **Filter JavaScript Presisi:** Memastikan hanya data transaksi 7 hari terakhir yang dianalisis.
- **Analisis AI Cerdas:** Menggunakan model AI via OpenRouter untuk memberikan 1 saran penghematan konkret.
- **Notifikasi Telegram:** Laporan dikirim langsung ke pesan pribadi pengguna.

## 🛠️ Cara Penggunaan
1. Import file `Asa_Pengeluaran_Mingguan.json` ke n8n Anda.
2. Hubungkan dengan Google Sheets yang berisi kolom: Tanggal, Nama Pengeluaran, Kategori, dan Jumlah.
3. Sesuaikan Chat ID Telegram pada node Telegram.
4. Jalankan workflow.
---
