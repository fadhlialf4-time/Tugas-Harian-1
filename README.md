# Tugas-Harian-1
1. Tulis perintah CLI yang digunakan untuk membuat folder legacy_portfolio_dump/ beserta isi file dan subfolder di dalamnya sesuai instruksi di atas.
- Jawaban : mkdir, cd, mv, touch
2. Bagaimana cara menambahkan teks <h1>Homepage Lama</h1> ke dalam file index_lama.html menggunakan CLI? (bonus)
- Jawaban : echo "<h1>Homepage Lama</h1> > index_lama.html
3. Apa perintah untuk melihat seluruh isi dari folder legacy_portfolio_dump/, termasuk semua isi di subfolder-nya?
- Jawaban : cat src/legacy_portofolio_dump
4. Tulis perintah CLI yang kamu gunakan untuk membuat struktur folder baru my_portfolio_professional/ lengkap sesuai dengan format yang diberikan.
- Jawaban : mkdir my portofolio professional, mkdir docs, mkdir public, mkdr src, mkdir temporary_storage
5. File index_lama.html harus dipindahkan ke public/ dan diubah namanya menjadi index.html. Tulis perintah CLI untuk melakukan hal tersebut.
- Jawaban : mv ../public lalu mengubah nama tersebut adalah mv index_lama.html > index.html
6. Terdapat dua file dengan nama logo.png dari lokasi berbeda. Bagaimana kamu menangani file duplikat ini saat memindahkannya ke dalam folder public/assets/images/?
- Jawaban : pertama, masuk ke folder public/assets/images. Selanjutnya ketik mv ../../../ (cari nama file yang ada logo png), lalu titik, dan enter
7. File temp_draft.html, data_test.txt, dan folder versi_lama/ tidak lagi dibutuhkan. Tulis perintah untuk menghapus semuanya.
- Jawaban : rm-f
8. Bagaimana kamu memeriksa bahwa seluruh isi legacy_portfolio_dump/ telah dipindahkan atau dihapus dengan benar?
- Jawaban : dengan ketik "find" lalu ketik file tersebut periksa bahwa ada atau tidak
9. Perintah apa yang digunakan untuk menampilkan seluruh struktur folder my_portfolio_professional/ dari terminal?
- Jawaban : pwd
10. Tuliskan isi akhir dari file:
a. index.html (hasil rename dari index_lama.html)
- Jawaban : mv index_lama.html > index.html
b. README.md (hasil pemindahan dari legacy_portfolio_dump/)
- Jawaban : mv mv../../legacy_portofolio_dump/README.md
11. Apa manfaat menggunakan CLI dalam proses penataan proyek seperti ini?
- Jawaban : Dapat melatih kecepatan, konsistensi, dan efisiensi waktu
