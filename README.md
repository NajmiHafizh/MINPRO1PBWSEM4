# MINI PROJECT 1 PEMROGRAMAN BERBASIS WEB

- NAJMI HAFIZH MAULUDAN ZAIN
- 2409116028
- SISTEM INFORMASI A`24

---------------------------------------------------------------------------------------------------------------------------------------

## Tampilan pada section navbar dan home

<img width="1895" height="902" alt="image" src="https://github.com/user-attachments/assets/f3185fe3-aecf-4954-a6ec-9e2f97b81c1d" />

- Navbar berada di bagian paling atas halaman dan berfungsi sebagai navigasi utama. Menu yang tersedia terdiri dari Home, About Me, dan Certificates. Navbar dibuat menggunakan komponen Bootstrap agar tampilannya responsif.

- Section Home merupakan bagian pembuka dari website. Pada bagian ini terdapat perkenalan singkat, deskripsi mengenai minat di bidang Data Science dan Visualisasi Data, serta sebuah tombol yang mengarahkan ke bagian About Me. Selain itu, terdapat juga foto profil yang ditampilkan berdampingan dengan teks menggunakan sistem grid Bootstrap (row dan col-md-6). Penggunaan grid ini membuat tata letak menjadi lebih rapi serta otomatis menyesuaikan ketika d

## Tampilan pada section about me

<img width="1893" height="897" alt="image" src="https://github.com/user-attachments/assets/40abf14e-0eba-4b44-bee7-4a6fb5337557" />

Bagian About Me berisi penjelasan lebih lanjut mengenai latar belakang dan minat yang dimiliki. Pada section ini juga ditampilkan daftar skills dalam bentuk progress bar, seperti Pemrograman Python, Data Visualization, dan Data Science. Progress bar dibuat menggunakan komponen Bootstrap agar tampilannya lebih visual dan informatif. Selain itu, terdapat juga bagian pengalaman yang ditampilkan dalam bentuk list untuk memberikan gambaran singkat mengenai pengalaman yang pernah dilakukan.

## Tampilan pada section certificates dan footer

<img width="1897" height="899" alt="image" src="https://github.com/user-attachments/assets/6cf9aad2-e332-47d7-b1f8-d925245ba5d7" />

- Section Certificates menampilkan daftar sertifikat dalam bentuk card. Setiap card berisi gambar sertifikat, judul, serta deskripsi singkat mengenai pelatihan yang telah diikuti. Layout pada bagian ini menggunakan sistem grid Bootstrap (row dan col-md-4) sehingga pada layar besar akan tampil dalam tiga kolom, sedangkan pada layar kecil akan otomatis menyesuaikan menjadi satu kolom agar tetap nyaman dibaca.

- Footer terletak di bagian paling bawah halaman dan berisi informasi hak cipta. Warna footer disesuaikan dengan warna navbar agar tampilan website terlihat konsisten dan seimbang.

---------------------------------------------------------------------------------------------------------------------------------------

## Struktur HTML

Website ini menggunakan struktur dasar HTML yang lengkap, yaitu (!DOCTYPE html), (html), (head), dan (body).

Pada bagian (head) terdapat:
- Meta charset untuk mendukung karakter UTF-8
- Meta viewport agar tampilan responsif di perangkat mobile
- Link CDN Bootstrap untuk membantu proses styling dan layout
- Link file style.css untuk styling tambahan

Struktur ini digunakan agar halaman dapat ditampilkan dengan baik di berbagai perangkat serta mengikuti standar penulisan HTML yang benar.

## Navbar

- Navbar dibuat menggunakan komponen Bootstrap dengan class seperti navbar, navbar-expand-lg, dan navbar-dark.
- Class navbar-expand-lg berfungsi agar menu akan berubah menjadi toggle ketika ukuran layar lebih kecil dari ukuran large (lg).
- Navigasi menggunakan anchor dengan atribut href yang mengarah ke id masing-masing section, sehingga ketika diklik akan langsung menuju bagian yang sesuai di halaman.

## Section home

- Section ini menggunakan sistem grid Bootstrap dengan container, row, dan col-md-6.
- Pembagian kolom ini membuat teks dan gambar dapat ditampilkan berdampingan pada layar besar, namun tetap tersusun vertikal pada layar kecil.
- Tombol menggunakan class btn btn-primary dari Bootstrap untuk memberikan tampilan tombol yang konsisten dengan tema.

## Section about me

- Pada bagian ini digunakan komponen progress dan progress-bar dari Bootstrap untuk menampilkan skill dalam bentuk visual persentase.
- Persentase diatur menggunakan properti style="width: 80%" untuk menentukan panjang progress bar sesuai nilai skill.
- Bagian pengalaman ditampilkan menggunakan list (<ul> dan <li>) agar informasi tersusun dengan jelas dan mudah dibaca.

## Section certificates

Section ini menggunakan sistem grid dengan row dan col-md-4 untuk membagi layout menjadi tiga kolom pada layar besar.

Setiap sertifikat ditampilkan menggunakan komponen card Bootstrap yang terdiri dari:
- Gambar (card-img-top)
- Judul (card-title)
- Deskripsi (card-text)

Penggunaan card membuat tampilan lebih terstruktur dan konsisten.

## Struktur CSS

File style.css digunakan untuk menambahkan styling tambahan di luar Bootstrap.

Beberapa pengaturan yang dilakukan melalui CSS antara lain:
- Mengatur font dasar pada seluruh halaman
- Mengubah warna navbar agar lebih sesuai dengan desain
- Memberikan pengaturan pada progress bar
- Mengatur tampilan card dan gambar agar lebih rapi
- Mengatur tampilan footer
  
Penggunaan CSS ini bertujuan untuk memberikan sentuhan personal pada desain tanpa menghilangkan fungsi utama dari Bootstrap.

---------------------------------------------------------------------------------------------------------------------------------------
