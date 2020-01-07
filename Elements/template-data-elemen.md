# Template Penulisan Data Elemen

> Markdown is not a replacement for HTML, or even close to it. Its syntax is very small, corresponding only to a very small subset of HTML tags. The idea is not to create a syntax that makes it easier to insert HTML tags. In my opinion, HTML tags are already easy to insert. The idea for Markdown is to make it easy to read, write, and edit prose. HTML is a publishing format; Markdown is a writing format. Thus, Markdown’s formatting syntax only addresses issues that can be conveyed in plain text.

MESKIPUN DEMIKIAN atau TETAPI, kita dapat menggunakannya sebagai *database* atau repositori elemen behavioral yang akan memberi setidaknya dua keuntungan. *Pertama*, karena Markdown, kita dapat melakukan operasi CRUD tanpa bantuan software apapun selain alat tulis. *Kedua*, ... nanti dicari yang kedua. Untuk menuju ke hal tersebut ada beberapa yang harus dipatuhi supaya dokumen dengan template ini dapat dibaca dan dikelola oleh mesin seperti halnya database mengelola entrinya. Berikut ini adalah yang beberapa itu.

**SATU** &bull; Setiap elemen harus ditulis dalam satu blok terpisah dari blok elemen yang lain. Pemisahnya adalah SATU baris kosong.

**DUA** &bull; Setiap blok elemen terdiri dari dua subblok, yaitu subblok judul dan subblok tabel. Subblok judul berisi nama formal elemen dan ditulis sebagai Heading level 3 dengan penanda tiga tanda pagar dan satu sepasi (`### `). Subblok ini juga dipisahkan oleh satu baris kosong dengan subblok tabel.

**TIGA** &bull; Subblok tabel berisi tabel dua kolom. Kolom pertama adalah `key` dan yang kedua berisi `value`. Cara penulisan subblok tabel dapat dilihat pada contoh-contoh di bawah. Yang terpenting adalah bahwa baris pertama harus memuat nama elemen dengan penulisan seperti berikut: `Nama | Analytical Thinking`. Dan untuk terbaca sebagai tabel, baris kedua hanya boleh berisi penanda ini: `:----|:----`. Baris ketiga dan seterusnya dari subblok tabel diperuntukkan untuk memuat data lain dari setiap elemen, tetapi yang harus ada (selain `Nama`) adalah `Kode` dan `Definisi`. Tanpa `Nama`, `Kode`, dan `Definisi` data dalam subblok tabel akan diabaikan.

O ya, **EMPAT** &bull; Isian pada subblok judul (`### <Nama Elemen>`) harus *matching* dengan isian kolom kedua baris pertama dari subblok tabel (`Nama | <Nama Elemen>`). Kalau tidak cocok, datanya juga akan diabaikan. Sebenarnya, keberadaan subblok judul juga akan membuat dokumen ini menjadi lebih enak dibaca.

---

### Manage Relations

Nama | Manage Relations
:----|:----
Kode | MNRL
Alias | Socializing
Definisi | Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Achievement Drive

Nama  | Achievement Drive
:-----|:----
Kode  | ACHD
Alias | Semangat Tempur
Definisi | Lorem ipsum dolor sit amet, **consectetur adipisicing** elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. *Ut enim ad minim veniam*, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Ascent Drive

Nama  | Ascent Drive
:-----|:----
Kode  | ASCD
Alias | Dorongan Mendaki
Definisi | Karakter yang menggambarkan semangat tempur, dapat diukur melalui setidaknya dua metode: Gerkhin dan Absol.
Deskripsi | Lorem ipsum dolor sit amet, **consectetur adipisicing** elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. *Ut enim ad minim veniam*, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
