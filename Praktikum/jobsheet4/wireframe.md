
# Wireframe & User Flow SIMPUS-Mini

## Wireframe Teks

### 1. Login
```
[Halaman Login]
---------------------------------
| Username: [__________]         |
| Password: [__________]         |
| [ Login ]                      |
---------------------------------
```

### 2. Dashboard Petugas
```
[Dashboard Petugas]
---------------------------------
| Menu: Beranda | Buku | Anggota |
|       Peminjaman | Pengembalian | Riwayat |
---------------------------------
| Ringkasan: Total Buku, Anggota, Sedang Dipinjam |
---------------------------------
```

### 3. Peminjaman
```
[Form Peminjaman]
---------------------------------
| Pilih Anggota: [Dropdown]      |
| Pilih Buku: [Dropdown]         |
| Tanggal Pinjam: [____]         |
| Tanggal Kembali: [____]        |
| [ Simpan ]                     |
---------------------------------
```

### 4. Pengembalian
```
[Form Pengembalian]
---------------------------------
| Cari Transaksi: [ID / Nama]    |
| Buku: [Judul Buku]             |
| Status: Dikembalikan           |
| [ Simpan ]                     |
---------------------------------
```

### 5. Riwayat
```
[Riwayat Transaksi]
---------------------------------
| ID | Anggota | Buku | Status   |
| 01 | Budi    | Algoritma | Pinjam |
| 02 | Sari    | Basis Data | Kembali |
---------------------------------
```

---

## User Flow

### Tamu
1. Buka aplikasi → langsung ke **Beranda**.
2. Bisa lihat **Daftar Buku**.
3. Tidak bisa tambah/edit buku, tidak bisa pinjam.

### Petugas
1. Login → masuk ke **Dashboard Petugas**.
2. Bisa akses:
   - CRUD Buku & Anggota
   - Transaksi **Peminjaman** & **Pengembalian**
   - Lihat **Riwayat** transaksi
3. Logout → kembali jadi Tamu.

---

## Diagram Alur (Flowchart ASCII)

```
[Tamu] --------------------------> [Beranda] --> [Daftar Buku]
   |
   | (Login)
   v
[Petugas] --> [Dashboard] --> [CRUD Buku/Anggota]
                       |--> [Peminjaman]
                       |--> [Pengembalian]
                       |--> [Riwayat]
```

