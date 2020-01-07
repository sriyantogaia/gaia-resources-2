Gaia Behavioral WorkBook
========================

Bagian ini berisi DRAFT format data WorkBook untuk setiap jenis (modul) tes behavioral. Walaupun setiap modul (SJT, CSI, dsb) memiliki ciri dan kontent yang berbeda, sebenarnya, selain FGD dan Wawancara, mereka memiliki konstruk yang kurang lebih sama atau mirip. Adanya kesamaan/kemiripan konstruk tersebut memungkinkan dibuatnya sebuah model dokumen yang dapat dipakai oleh hampir seluruh modul, dan dengan demikian memudahkan untuk dilakukan validasi dan pengembangan.

Tabel yang termuat di file [`modules-meta.csv`](./modules-meta.csv) menunjukkan sebagian konstruk dari seluruh modul yang ada di Gaia. Modul yang kolom WorkBook-nya bertanda **ok**, sebagian kontentnya sudah dibukukan (sekali lagi, masih DRAFT) dan dapat dilacak di folder [`xml`](./xml/).

Format XML adalah format formal penulisan modul yang akan diakomodasi *dalam* aplikasi yang saat ini sedang dikembangkan. Walupun demikian, untuk pengembangan bisa saja dipakai format Markdown, atau Markdown dengan dengan kustomisasi, dan apabila sudah final akan dikonversi menjadi format formal yaitu XML.

*Tugas saat ini adalah mengkritisi draft ini untuk menemukan konstruk yang baku, tetapi tetap fleksibel, untuk setiap jenis modul atau test*. Setelah konstruk baku dianggap final selanjutnya akan dibuat `XMLSchema` yang akan berfungsi sebagai 1) validator bagi setiap dokumen WorkBook, dan 2) platform pengembangan modul. File [`workbook.rng`](./workbook.rng) adalah contoh `XML Schema` untuk WorkBook yang dibuat dalam format **Relax NG**.

### Materi gambar, tabel dsb

Seluruh materi WorkBook yang berupa gambar, tabel, diagram, dsb. harus disediakan dalam format bitmap (PNG atau JPG) untuk menjamin materi tersebut dapat dilihat dalam visual yang seragam apa pun browsernya dan settingan browsernya. Ini juga untuk menghindari terjadinya *accidental edits*.
