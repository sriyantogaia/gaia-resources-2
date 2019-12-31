Nomenklatur Elemen Behavioral
=============================

Elemen Behavioral, atau Elemen, adalah sebuah pernyataan yang menggambarkan kualitas 
sebuah aspek behavioral yang dianggap bisa diukur secara ilmiah. Untuk keperluan
pengukuran tersebut, setiap elemen harus memiliki sejumlah atribut yang bisa dipakai
untuk membedakan satu elemen dengan elemen lainnya. Atribut minimal yang harus ada
pada sebuah elemen adalah:

1. Nama (`name`)
2. Simbol (`symbol`)
3. Definisi (`definition`)

Selain ketiga atribut tersebut, atribut baru dapat diciptakan untuk mendukung kebutuhan
tertentu. Di bawah ini adalah sebuah skenario;

1. Nama (`name`)
2. Simbol (`symbol`)
3. Definisi (`definition`)
4. Alias (`alias`), yaitu nama lain yang bisa dipakai
5. Def-EN (`definition-en`), definisi dalam Bahasa Inggris
6. Def-Mil (`definition-mil`), definisi milenial

### Nama Elemen

Atribut Nama (`name`) adalah atribut yang merepresentasikan sebuah elemen, terdiri
dari satu atau lebih kata, tetapi sebaiknya tetap pendek supaya mudah diingat. Nama
elemen sebisa mungkin tidak ambigu dan tidak *misleading*. Walaupun dimungkinkan
sebuah elemen mempunyai nama yang sama dengan nama elemen lain, *sangat* disarankan
setiap elemen memiliki nama yang unik.

### Simbol Elemen

Atribut Simbol (`symbol`) adalah atribut formal yang dipakai sebagai pembeda 
(*identifier*) antara satu elemen dengan elemen yang lain, dan karena itu `symbol` 
setiap elemen harus unik. Simbol element terdiri dari empat huruf kapital dan sebaiknya
berupa singkatan dari nama formal elemennya. (Seperti di pasar modal, setiap perusahaan)
memiliki simbol yang unik, misalnya **MSFT** merupakan simbol dari perusahaan Microsoft)

### Definisi Elemen

Atribut Definisi (`definition`) adalah atribut yang mendefinisikan sebuah elemen secara
padat, singkat, dan sekaligus tepat. Atribut ini menjadi semacam kamus rujukan (untuk
mengetahui arti sebenarnya) seandainya terdapat dua atau lebih elemen yang memiliki nama 
yang sama.

Atribut Definisi ditulis dalam Bahasa Indonesia baku dengan mempertimbangkan aspek
*ketidaklekangan* arti sehingga dapat dipakai dalam kurun waktu yang lama.

### Elemen Sederhana

Elemen Sederhana (`SimpleElement`) adalah elemen behavioral yang dapat diukur secara 
mandiri tanpa intervensi atau pengaruh dari hasil pengukuran elemen lain.

### Elemen Komposit

Elemen Komposit (`CompositeElement`) adalah elemen behavioral yang hanya dapat diukur
melalui pengukuran satu atau lebih elemen lain.

### Pengukuran Elemen

Yang dimaksud dengan Pengukuran Elemen adalah *aktivitas pengukuran kualitas sebuah 
elemen behavioral dari seseorang atau sebuah organisasi berdasarkan bukti-bukti yang 
cukup dan dengan menerapkan metode yang dapat dipertanggungjawabkan*.

Metode pengukuran elemen merupakan bagian tak terpisahkan dari modul atau paket Tes 
Behavioral, dan setiap modul atau paket memiliki metode pengukuranyang berbeda dari 
modul atau paket yang lain. Meskipun demikian, setiap pengukuran dapat dibedakan dalam
tiga jenis berikut ini:

- pengukuran langsung yang menghasilkan skor (*direct score*)
- pengukuran *algo* yang melibatkan satu atau lebih input selain bukti
- interpretasi

#### Skor

Lorem ipsum...

#### Algo

Lorem ipsum...

#### Interpretasi

Lorem ipsum...

````
TODO: Write contents.
````
