
| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC07: Lihat Kalender Akademik** |
| **Sumber Kebutuhan** | SIA-R07 |
| **Tujuan** | Civitas Akademika dapat melihat jadwal kegiatan akademik selama satu semester atau tahun ajaran berjalan |
| **Aktor Utama** | Civitas Akademika |
| **Pemicu** | Pengguna memilih fungsi atau menu untuk melihat kalender akademik |
| **Prasyarat** | Pengguna telah terautentikasi ke dalam sistem |
| **Pascakondisi Berhasil** | Sistem menampilkan informasi kalender akademik terkini secara lengkap |
| **Pascakondisi Gagal** | Kalender akademik gagal ditampilkan; sistem memunculkan pesan kesalahan koneksi atau data kosong |
| **Include** | - |
| **Collaboration** | - |


| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC08: Input Nilai Mata Kuliah** |
| **Sumber Kebutuhan** | SIA-R08 dan SIA-R12 |
| **Tujuan** | Dosen dapat memasukkan nilai mahasiswa untuk kelas mata kuliah yang diampunya |
| **Aktor Utama** | Dosen |
| **Pemicu** | Dosen memilih fungsi pencatatan/input nilai dan menentukan kelas mata kuliah yang akan dinilai |
| **Prasyarat** | Dosen telah terautentikasi; dosen adalah pengampu dari kelas mata kuliah yang dipilih |
| **Pascakondisi Berhasil** | Nilai mahasiswa tersimpan di dalam sistem dan status pengisian nilai kelas tersebut terbarui menjadi selesai |
| **Pascakondisi Gagal** | Nilai di luar rentang yang sah ditolak; tidak ada nilai baru yang tercatat atau diubah di dalam sistem |
| **Include** | - |
| **Collaboration** | SIA-CO01: Input Nilai Mata Kuliah |


| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC09: Lihat KHS** |
| **Sumber Kebutuhan** | SIA-R09 dan SIA-R12 |
| **Tujuan** | Mahasiswa dapat melihat Kartu Hasil Studi (KHS) pada semester terpilih |
| **Aktor Utama** | Mahasiswa |
| **Pemicu** | Mahasiswa memilih fungsi untuk melihat KHS dan menentukan komponen semester yang diinginkan |
| **Prasyarat** | Mahasiswa telah terautentikasi ke dalam sistem |
| **Pascakondisi Berhasil** | Sistem menampilkan KHS mahasiswa; hanya nilai yang sudah dipublikasikan yang ditampilkan |
| **Pascakondisi Gagal** | Nilai atau KHS tidak ditampilkan jika belum ada komponen nilai pada semester tersebut yang dipublikasikan |
| **Include** | - |
| **Collaboration** | SIA-CO02: Lihat KHS |



| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC10: Kelola Data Mahasiswa** |
| **Sumber Kebutuhan** | SIA-R10 |
| **Tujuan** | Admin Akademik dapat mengelola seluruh data induk mahasiswa di dalam sistem |
| **Aktor Utama** | Admin Akademik |
| **Pemicu** | Admin memilih menu utama pengelolaan data mahasiswa |
| **Prasyarat** | Admin Akademik telah terautentikasi ke dalam sistem |
| **Pascakondisi Berhasil** | Sistem menampilkan halaman menu utama pengelolaan data mahasiswa |
| **Pascakondisi Gagal** | Halaman menu utama pengelolaan data gagal dimuat; data master mahasiswa tetap aman tidak berubah |
| **Include** | - |
| **Collaboration** | - |


| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC11: Tambah Data Mahasiswa** |
| **Sumber Kebutuhan** | SIA-R11 |
| **Tujuan** | Mendaftarkan rekam data mahasiswa baru ke dalam basis data sistem akademik |
| **Aktor Utama** | Admin Akademik |
| **Pemicu** | Admin memilih aksi penambahan data pada halaman kelola data mahasiswa |
| **Prasyarat** | Admin Akademik telah berada di dalam menu SIA-UC10 Kelola Data Mahasiswa |
| **Pascakondisi Berhasil** | Data identitas mahasiswa baru berhasil tersimpan ke sistem dan mendapatkan nomor induk (NIM) aktif |
| **Pascakondisi Gagal** | Mahasiswa baru tidak terdaftar; sistem menolak entri data yang tidak lengkap atau memiliki duplikasi NIM |
| **Include** | - |
| **Collaboration** | - |


| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC12: Ubah Data Mahasiswa** |
| **Sumber Kebutuhan** | SIA-R11 |
| **Tujuan** | Memperbarui informasi profil atau status akademik milik mahasiswa yang sudah terdaftar |
| **Aktor Utama** | Admin Akademik |
| **Pemicu** | Admin memilih entitas mahasiswa tertentu dan menekan tombol edit/ubah data |
| **Prasyarat** | Admin Akademik telah berada di dalam menu SIA-UC10 Kelola Data Mahasiswa |
| **Pascakondisi Berhasil** | Perubahan informasi mahasiswa berhasil diperbarui dan disimpan ke dalam basis data sistem |
| **Pascakondisi Gagal** | Perubahan dibatalkan; data mahasiswa tidak berubah dan kembali ke informasi sebelum pengeditan dilakukan |
| **Include** | - |
| **Collaboration** | - |


| Elemen | Spesifikasi |
| :--- | :--- |
| **Use Case ID & Nama** | **SIA-UC13: Hapus Data Mahasiswa** |
| **Sumber Kebutuhan** | SIA-R11 |
| **Tujuan** | Menghapus atau menonaktifkan rekam data mahasiswa terpilih dari sistem |
| **Aktor Utama** | Admin Akademik |
| **Pemicu** | Admin memilih entitas data mahasiswa tertentu dan menekan tombol hapus |
| **Prasyarat** | Admin Akademik telah berada di dalam menu SIA-UC10 Kelola Data Mahasiswa |
| **Pascakondisi Berhasil** | Data mahasiswa berhasil terhapus secara permanen atau status keaktifannya dinonaktifkan dari sistem |
| **Pascakondisi Gagal** | Data mahasiswa gagal dihapus; informasi record mahasiswa tetap tercantum aktif di dalam sistem |
| **Include** | - |
| **Collaboration** | - |
