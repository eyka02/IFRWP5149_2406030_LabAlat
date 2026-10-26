<!--  Indeks tugas skenario SIA -->
| ID Use Case | Nama Use Case | Aktor | Catatan Pemetaan / Kondisi |
| :--- | :--- | :--- | :--- |
| **SIA-UC07** | Lihat Kalender Akademik | Civitas Akademika | Berlaku untuk Mahasiswa dan Dosen. |
| **SIA-UC08** | Input Nilai Mata Kuliah | Dosen | **Prasyarat:** Dosen pengampu. <br> **Alternatif:** Nilai tidak sah ditolak. <br> **Realisasi:** SIA-CO01. |
| **SIA-UC09** | Lihat KHS | Mahasiswa | Hanya nilai dipublikasikan. <br> **Realisasi:** SIA-CO02. |
| **SIA-UC10** | Kelola Data Mahasiswa | Admin Akademik | Langkah bersama yang dirujuk UC11, UC12, UC13. |
| **SIA-UC11** | Tambah Data Mahasiswa | Admin Akademik | Khusus dari UC10 (Data baru tersimpan). |
| **SIA-UC12** | Ubah Data Mahasiswa | Admin Akademik | Khusus dari UC10 (Data berubah). |
| **SIA-UC13** | Hapus Data Mahasiswa | Admin Akademik | Khusus dari UC10 (Data terhapus). <br> **Syarat:** Tidak ada data aktif. |
