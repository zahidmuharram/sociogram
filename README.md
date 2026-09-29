# Sosiogram

Aplikasi web untuk mengolah data sosiometri dan menggambar sosiogram dari pilihan antaranggota kelompok. Dirancang untuk asesmen psikologi di setting komunitas, dan dapat juga dipakai di kelas, kelompok pertemanan, dan organisasi.

**Alamat aplikasi:** [https://zahidmuharram.github.io/sociogram/]

Aplikasi berjalan sepenuhnya di browser. Tidak ada akun, tidak ada instalasi.

## Fitur

- **Dua model sosiogram.**
  - *Model target*: anggota diletakkan pada lingkaran konsentris menurut kategori status. Yang paling populer berada di pusat.
  - *Model jaringan*: anggota diletakkan menurut kedekatan hubungan, dengan warna dan bentuk simpul menurut jenis kelamin atau grup.
- **Satu sampai empat kriteria** dalam satu proyek, termasuk kriteria negatif (menolak). Contoh: teman paling dekat, diajak menggerakkan kegiatan, tempat meminta pendapat.
- **Bobot tiap peringkat.** Pilihan pertama, kedua, dan ketiga dapat diberi poin berbeda. Bobot awal: 1 pilihan = 1; 2 pilihan = 2 dan 1; 3 pilihan = 3, 2, dan 1.
- **Kategori status berbasis simpangan baku.** Skor terbobot diubah menjadi skor z, lalu dikelompokkan sebagai Populer, Rata-rata, Terabaikan, atau Isolat. Batas awal: z ≥ +1,0 untuk Populer dan z ≤ −0,5 untuk Terabaikan. Batas ini dapat diubah. Skor 0 selalu Isolat.
- **Klasifikasi Coie** (Populer, Ditolak, Terabaikan, Kontroversial, Rata-rata) bila kriteria positif dan negatif dipakai bersamaan.
- **Indeks kelompok:** pasangan timbal balik, rangkaian timbal balik, indeks kohesi, resiprositas, dan kecenderungan memilih sesama jenis kelamin atau sesama grup.
- **Pilihan tampilan garis:** warna menurut peringkat, kriteria, atau timbal balik; garis putus-putus untuk membedakan pilihan berbalas dan satu arah; ketebalan menurut peringkat.
- **Interaktif:** klik anggota untuk menyorot pilihan yang diberikan dan diterimanya; geser simpul untuk merapikan letak.
- **Narasi hasil otomatis** yang menyesuaikan konteks (kelas, kelompok pertemanan, organisasi, organisasi masyarakat, lingkungan warga, kelompok dampingan).
- **Ekspor** gambar (PNG dan SVG) dan tabel hasil (Excel). Setiap hasil ekspor diberi tanda **RAHASIA** serta nama penanggung jawab data dan pengembang aplikasi.

## Cara memakai

1. **Instrumen.** Isi judul kegiatan, nama Anda pada kolom *Penanggung jawab data*, dan konteks kelompok. Atur kriteria, jumlah pilihan, dan bobot sesuai instrumen yang dipakai.
2. **Data.** Klik *Kosongkan dan gunakan data sendiri* (data awal hanyalah contoh yang digenerate secara acak). Masukkan anggota beserta pilihannya dengan mengetik, menempel dari Excel, atau mengunggah berkas. Kotak merah menandai nama yang tidak terbaca, ambigu, ganda, atau memilih diri sendiri.
3. **Sosiogram.** Pilih model, label, dan tampilan garis. Unduh sebagai PNG atau SVG.
4. **Hasil.** Baca narasi, tabel individu, sosiomatriks, dan pasangan timbal balik. Unduh sebagai Excel.

Data tersimpan otomatis di browser yang sama, tetapi tidak berpindah antarperangkat. Unduh berkas Excel sebagai cadangan sebelum menutup halaman.

## Privasi dan etika penggunaan

- Data yang dimasukkan diproses di browser dan tidak dikirim ke server pengembang.
- Data pilihan dan penolakan bersifat sensitif. Simpan dengan aman, jangan unggah ke grup obrolan atau media sosial, dan gunakan label nomor pada gambar yang ditampilkan kepada anggota atau pihak lain.
- Skor dan kategori menggambarkan posisi anggota dalam peta pilihan, bukan penyebabnya. Skor nol tidak otomatis berarti kesulitan sosial. Interpretasi perlu dilengkapi observasi dan wawancara, dan hasil sosiometri tidak boleh menjadi satu-satunya dasar keputusan tentang seseorang.
- Pada kelompok yang sangat kecil, hasil lebih mudah dikenali per individu. Pertimbangkan hal ini sebelum hasil dibagikan.

## Batasan

- Aplikasi memerlukan koneksi internet untuk memuat pustaka Excel dan huruf.
- Kualitas hasil bergantung pada kualitas instrumen dan kejujuran pilihan responden.
- Sosiogram dari kelompok kecil bersifat deskriptif dan bukan uji statistik.

## Dasar metodologi

- Moreno, J. L. (1934). *Who Shall Survive?* Nervous and Mental Disease Publishing Co.
- Coie, J. D., Dodge, K. A., & Coppotelli, H. (1982). Dimensions and types of social status: A cross-age perspective. *Developmental Psychology, 18*(4), 557–570.

## Pengembang

**Hammad Zahid Muharram, M.Psi., Psikolog**

Untuk pertanyaan, laporan kendala, atau izin penggunaan di luar keperluan pembelajaran, hubungi pengembang: 
**zahid.muharram@unpad.ac.id**

Cara mengutip:

> Muharram, H. Z. (2026). *Sosiogram* [Aplikasi web]. [tautan aplikasi]

## Lisensi

Hak Cipta © 2026 Hammad Zahid Muharram, M.Psi., Psikolog. Seluruh hak dilindungi. Lihat berkas [LICENSE](LICENSE).

Pustaka pihak ketiga tetap tunduk pada lisensinya masing-masing: SheetJS Community Edition (Apache-2.0) dan huruf Literata serta Public Sans dari Google Fonts (SIL Open Font License).
