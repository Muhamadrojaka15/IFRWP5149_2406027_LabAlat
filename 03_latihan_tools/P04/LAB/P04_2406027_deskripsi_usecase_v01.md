<!-- Tabel 4.x Spesifikasi Use Case LAB-UC03 -->

+---------------------------+--------------------------------------------------------------+
| Elemen                    | LAB-UC03: Ajukan Peminjaman                                  |
+---------------------------+--------------------------------------------------------------+
| ID dan nama               | LAB-UC03: Ajukan Peminjaman                                  |
+---------------------------+--------------------------------------------------------------+
| Sumber kebutuhan          | LAB-R03, LAB-R04, dan LAB-R07                                |
+---------------------------+--------------------------------------------------------------+
| Tujuan                    | Menghasilkan pengajuan peminjaman yang tersimpan             |
+---------------------------+--------------------------------------------------------------+
| Aktor utama               | Peminjam (Mahasiswa atau Dosen, diwarisi dari aktor umum)    |
+---------------------------+--------------------------------------------------------------+
| Pemicu                    | Peminjam memilih fungsi pengajuan peminjaman                |
+---------------------------+--------------------------------------------------------------+
| Prasyarat                 | Peminjam telah terautentikasi; data peralatan tersedia      |
+---------------------------+--------------------------------------------------------------+
| Pascakondisi berhasil     | Pengajuan tersimpan dengan nomor dan status                 |
|                           | Menunggu Keputusan                                           |
+---------------------------+--------------------------------------------------------------+
| Pascakondisi gagal        | Tidak ada pengajuan baru yang berhasil tersimpan            |
+---------------------------+--------------------------------------------------------------+
| Generalization            | Tidak ada (bukan bagian hierarki use case)                  |
+---------------------------+--------------------------------------------------------------+
| Include                   | LAB-UC04: Periksa Ketersediaan                               |
+---------------------------+--------------------------------------------------------------+
| Extension point           | Bukti pengajuan tersedia, pada langkah 6                    |
+---------------------------+--------------------------------------------------------------+
| Extend                    | LAB-UC05: Cetak Bukti Pengajuan, jika                        |
|                           | [mahasiswa memilih cetak]                                    |
+---------------------------+--------------------------------------------------------------+
| Collaboration             | LAB-CO01: Ajukan Peminjaman                                  |
+---------------------------+--------------------------------------------------------------+
| Aturan bisnis atau asumsi | Pencetakan bukti hanya tersedia bagi Mahasiswa               |
|                           | (asosiasi khusus ke LAB-UC05); perpindahan fisik alat       |
|                           | tidak terjadi di sistem                                      |
+---------------------------+--------------------------------------------------------------+