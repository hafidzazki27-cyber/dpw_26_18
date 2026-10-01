# Wireframe & User Flow SIMPUS-Mini (Versi Alternatif)

## 1. Login
+-----------------------------------+
|   SIMPUS-Mini - Login             |
+-----------------------------------+
| Username : [__________]           |
| Password : [__________]           |
| [ Login ]   [ Register ]          |
+-----------------------------------+

---

## 2. Dashboard Petugas
+------------------------------------------------+
| Menu: [Buku] [Anggota] [Peminjaman] [Pengembalian] [Riwayat] [Logout] |
+------------------------------------------------+
| Ringkasan Data:                                |
| - Total Buku: 120                              |
| - Total Anggota: 45                            |
| - Sedang Dipinjam: 18                          |
+------------------------------------------------+
| Aksi Cepat: [+ Tambah Buku] [+ Tambah Anggota] |
+------------------------------------------------+

---

## 3. Form Peminjaman
+-----------------------------------+
| Peminjaman Baru                   |
+-----------------------------------+
| Anggota : [Dropdown]              |
| Buku    : [Dropdown stok > 0]     |
| Tgl Pinjam : [Auto Today]         |
| Tgl Kembali: [____]               |
| [ Simpan ]                        |
+-----------------------------------+

---

## 4. Form Pengembalian
+-----------------------------------+
| Pengembalian Buku                 |
+-----------------------------------+
| Cari Transaksi : [ID/Nama]        |
| Buku : [Judul Buku]               |
| Status : [Dipinjam → Dikembalikan]|
| [ Simpan ]                        |
+-----------------------------------+

---

## 5. Riwayat Transaksi
+------------------------------------------------+
| ID | Anggota | Buku        | Status   | Tgl Pinjam | Tgl Kembali |
| 01 | Budi    | Algoritma   | Pinjam   | 01/09/2026 | -           |
| 02 | Sari    | Basis Data  | Kembali  | 02/09/2026 | 10/09/2026  |
+------------------------------------------------+

---

# User Flow Singkat
- **Tamu**: hanya lihat katalog buku → tidak bisa CRUD/Transaksi.  
- **Petugas**: login → Dashboard → pilih menu → lakukan CRUD/Transaksi → logout.  
  
