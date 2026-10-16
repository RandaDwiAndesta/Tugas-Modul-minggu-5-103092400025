"# Tugas-Modul-minggu-5-103092400025" 
1. Pengertian Bootstrap
Bootstrap adalah framework CSS yang digunakan untuk mempermudah proses pembuatan tampilan website agar lebih menarik, konsisten, dan responsif. Bootstrap menyediakan berbagai komponen siap pakai, seperti navbar, tombol, form, card, serta sistem grid untuk mengatur tata letak halaman.
Kegunaan Bootstrap adalah mempercepat proses pengembangan website, mengurangi penulisan CSS dari awal, dan membantu membuat tampilan website yang dapat menyesuaikan ukuran layar komputer, tablet, maupun smartphone.
2. Memasang Bootstrap
Bootstrap dapat digunakan pada project dengan beberapa cara berikut.
1. Menggunakan CDN (Content Delivery Network)
   Menghubungkan file CSS dan JavaScript Bootstrap melalui URL CDN tanpa perlu mengunduh file Bootstrap secara manual.
2. Mengunduh file Bootstrap
   Mengunduh file Bootstrap dari website resminya, kemudian menyimpan file CSS dan JavaScript ke dalam folder project.
3. Menggunakan package manager
   Memasang Bootstrap melalui package manager seperti npm agar dapat digunakan dalam project pengembangan web.
4. Menggunakan framework atau build tools
   Mengintegrasikan Bootstrap ke dalam project menggunakan tools seperti Vite atau sistem build lainnya.
Pada tugas ini, metode yang digunakan adalah CDN Bootstrap versi 5.3.8, karena praktis dan tidak memerlukan instalasi tambahan.
3. Grid dan Breakpoint
Grid adalah sistem tata letak Bootstrap yang membagi halaman menjadi 12 kolom. Grid digunakan untuk mengatur posisi dan lebar elemen agar tersusun rapi serta dapat menyesuaikan ukuran layar.
Beberapa class grid Bootstrap antara lain:
- container: membungkus konten dengan lebar yang menyesuaikan ukuran layar.
- row: membuat baris untuk menampung kolom.
- col: membuat kolom dengan pembagian ruang secara otomatis.
- col-md-6: membuat kolom selebar 6 dari 12 kolom mulai dari breakpoint medium.
- col-lg-4: membuat kolom selebar 4 dari 12 kolom mulai dari breakpoint large.
Breakpoint adalah batas ukuran layar yang digunakan Bootstrap untuk menyesuaikan tampilan website pada perangkat yang berbeda.
Breakpoint	Ukuran layar minimal
xs	Di bawah 576 px
sm	576 px
md	768 px
lg	992 px
xl	1200 px
xxl	1400 px
Dengan grid dan breakpoint, elemen website dapat ditampilkan dengan lebar dan susunan yang sesuai, baik pada layar ponsel maupun komputer.
4. Class Bootstrap dan Kegunaannya
Berikut beberapa class Bootstrap beserta kegunaannya.
Class	Kegunaan
container	Membatasi dan merapikan area konten halaman.
navbar	Membuat navigasi website.
btn	Membuat tombol.
form-control	Memberikan tampilan standar pada input form.
form-check	Mengatur tampilan checkbox dan radio button.
text-center	Membuat teks rata tengah.
d-flex	Mengaktifkan tata letak flexbox.
mt-3	Memberikan margin atas.
p-4	Memberikan padding pada semua sisi.
shadow	Menambahkan bayangan pada elemen.
img-fluid	Membuat gambar responsif.
bg-primary	Memberikan warna latar belakang utama Bootstrap.
5. Gambar Responsif
Agar gambar pada website dapat menyesuaikan ukuran layar perangkat, Bootstrap menyediakan class img-fluid.
Contoh penggunaannya:
<img src="gambar.jpg" class="img-fluid" alt="Gambar">


Class img-fluid membuat gambar memiliki lebar maksimum 100% dari elemen induknya dan tinggi otomatis mengikuti proporsi gambar. Dengan demikian, gambar tidak melampaui lebar kontainer dan dapat menyesuaikan ukuran layar perangkat.
