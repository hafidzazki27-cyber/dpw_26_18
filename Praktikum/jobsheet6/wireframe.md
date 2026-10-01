

## 1. Aktor Sistem
**Tamu**
- Hanya bisa melihat katalog buku (Beranda, Daftar Buku).
- Tidak perlu login.

**Petugas**
- Login untuk mengakses seluruh fitur CRUD dan transaksi peminjaman/pengembalian.

---

## 2. User Flow

### A. Peminjaman Buku
[Petugas Login] → [Dashboard] → [Menu “Peminjaman Baru”] → [Pilih Anggota] → [Pilih Buku (stok > 0)] → [Simpan] → [Stok berkurang 1] → [Kembali ke Dashboard]

### B. Pengembalian Buku
[Dashboard] → [Menu “Pengembalian”] → [Cari transaksi aktif] → [Tandai “Dikembalikan”] → [Stok bertambah 1] → [Kembali ke Dashboard]

---

## 3. Wireframe Halaman

### 3.1 Login
```
+--------------------------------------+
|              SIMPUS-Mini             |
+--------------------------------------+
| Username : [______________]          |
| Password : [______________]          |
| [   Masuk   ]                        |
| Belum punya akun? Daftar di sini     |
+--------------------------------------+
```

### 3.2 Dashboard Petugas
```
+-----------------------------------------------------+
| Beranda | Buku | Anggota | Peminjaman | Logout      |
+-----------------------------------------------------+
| Ringkasan: Total Buku | Total Anggota | Sedang Dipinjam |
+-----------------------------------------------------+
| Aksi Cepat: +Peminjaman Baru | +Pengembalian       |
+-----------------------------------------------------+
| Transaksi Terbaru: Anggota | Buku | Tgl | Status   |
+-----------------------------------------------------+
```

### 3.3 Form Peminjaman
```
+--------------------------------------+
| Form Peminjaman Buku                 |
+--------------------------------------+
| Anggota : [dropdown]                 |
| Buku    : [dropdown stok>0]          |
| Tgl Pinjam : [auto: hari ini]        |
| [ Simpan Peminjaman ]                |
+--------------------------------------+
```

### 3.4 Form Pengembalian
```
+--------------------------------------+
| Pengembalian Buku                    |
+--------------------------------------+
| Cari transaksi aktif: [input]        |
| Anggota | Buku | Tgl | [Kembalikan]  |
+--------------------------------------+
```

### 3.5 Riwayat Peminjaman
```
+--------------------------------------+
| Riwayat Peminjaman — Siti Aminah     |
+--------------------------------------+
| Buku            | Pinjam | Kembali | Status |
| Laskar Pelangi  | 01/07  | 10/07   | Selesai|
| Bumi Manusia    | 15/07  | —       | Dipinjam|
+--------------------------------------+
```

---

