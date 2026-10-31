## Software Requirements Specification (SRS)

## Web Profil Kelompok dengan Content Management System (CMS)

## 1. Pendahuluan

## 1.1 Tujuan

Proyek ini bertujuan untuk membangun sebuah website profil kelompok yang menampilkan informasi anggota, biodata, deskripsi diri (About Me), serta galeri foto. Website dilengkapi dengan Content Management System (CMS) agar pengelola dapat memperbarui konten tanpa perlu mengubah kode program secara langsung.

## 1.2 Ruang Lingkup

Website terdiri dari dua bagian utama:

- Halaman publik: Menampilkan profil kelompok, biodata anggota, deskripsi diri, dan galeri foto.

- Halaman admin (CMS): Digunakan untuk mengelola konten website melalui sistem login.

Pemilihan teknologi, framework, dan tema desain dibebaskan kepada masing-masing

kelompok.

## 2. Kebutuhan Fungsional

## FR-01 — Login

Sistem menyediakan fitur login bagi admin untuk mengakses halaman CMS. Hanya pengguna yang berhasil melakukan autentikasi yang dapat mengelola konten website.

## FR-02 — Pengelolaan Biodata

Admin dapat menambahkan, melihat, mengubah, dan menghapus biodata anggota kelompok melalui CMS. Informasi biodata ditampilkan pada halaman publik.

## FR-03 — Pengelolaan About Me

Admin dapat menambahkan, melihat, mengubah, dan menghapus deskripsi diri anggota kelompok. Informasi tersebut ditampilkan pada halaman profil anggota.

## FR-04 — Pengelolaan Galeri

Admin dapat menambahkan foto, melihat daftar foto, mengubah informasi atau keterangan foto, serta menghapus foto melalui CMS. Foto yang telah ditambahkan akan ditampilkan pada halaman galeri publik.

## FR-05 — Tampilan Website Publik

Sistem menampilkan informasi profil kelompok, biodata anggota, About Me, dan galeri foto yang telah tersimpan di dalam sistem.


## 3. Kebutuhan Nonfungsional

## NFR-01 — Kemudahan Penggunaan

Website memiliki antarmuka yang mudah dipahami dan digunakan, baik pada halaman publik maupun CMS.

## NFR-02 — Responsivitas

Website dapat diakses dan digunakan melalui perangkat desktop maupun perangkat mobile.

## NFR-03 — Keamanan

Sistem login harus melakukan validasi kredensial pengguna. Halaman CMS dan operasi pengelolaan konten hanya dapat diakses oleh pengguna yang telah terautentikasi dan memiliki hak akses yang sesuai.

## NFR-04 — Konsistensi Data

Perubahan konten melalui CMS harus tersimpan dan tercermin pada halaman publik tanpa perlu mengubah kode program secara manual.

## 4. Ketentuan Implementasi

- 1. Teknologi yang digunakan bebas, baik native maupun framework.

- 2. Tema, tata letak, dan desain visual website dibebaskan kepada masing-masing kelompok.

- 3. Sistem harus memiliki halaman publik dan halaman CMS yang terintegrasi.

- 4. Fitur CRUD harus berfungsi untuk biodata, About Me, dan galeri foto.

- 5. Kelompok wajib mengikuti minimal satu kali asistensi untuk membahas perkembangan proyek, kendala implementasi, atau evaluasi hasil pengerjaan.

## 5. Kriteria Penerimaan

Proyek dinyatakan memenuhi kebutuhan apabila:

- Website dapat menampilkan profil kelompok, biodata, About Me, dan galeri foto.

- Admin dapat login ke CMS menggunakan kredensial yang valid.

- Admin dapat melakukan CRUD terhadap biodata, About Me, dan galeri foto.

- Perubahan konten tersimpan dan ditampilkan dengan benar pada website publik.

- Website dapat digunakan pada desktop dan perangkat mobile.

- Kelompok telah mengikuti minimal satu kali asistensi.


## 6. Jadwal Proyek

Seluruh kelompok wajib mematuhi jadwal berikut:

| Kegiatan | Tanggal |
| --- | --- |
| Batas akhir pengumpulan proyek (deadline) | 30 Oktober 2026 |
| Presentasi proyek | 31 Oktober 2026 |
