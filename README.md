# Mini Project 1 Praktikum PBW
Nama  : Nabila Imtiyaz Agustin

NIM   : 2409116011

Kelas : A

Sistem Informasi '2024

# Portofolio Website

Website portofolio personal yang menampilkan profil, pengalaman, skill, sertifikat, dan jurnal pribari. Dibuat menggunakan HTML, CSS, Bootsrap 5, dan Vue JS.

# Tampilan Setiap Section/Fitur

## 1. Navbar

<img width="1886" height="78" alt="image" src="https://github.com/user-attachments/assets/eafe9a59-6f50-4d12-a3fc-6efe51596266" />

Navbar berada di bagian atas website dan ketika discroll Navbar tetap kelihatan karena Navbar ini sifatnya Fixed. Di Navbar sendiri itu ada menu navigasi Home, About Me, Certificates, dan Journal yang mana ketika diklik oelh pengguna, akan berpindah atau bernavigasi ke menu yang diklik.

Navbar berguna untuk membantu pengguna antar section dengan smooth scroll.

## 2. Hero Section

<img width="1887" height="785" alt="image" src="https://github.com/user-attachments/assets/d6d41a36-6d52-4ad3-8094-be62d8a94a77" />

Hero section adalahtampilan pertama yang muncul saat website dibuka. Dalam hero section website portofolio ini terdapat fitur Nama lengkap, ada Deskripsi singkat nya sebagai tagline, lalu ada tombol Explore My Work, 

<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/8cf72f1f-2ca1-4f04-9e18-8549dcb69fd0" />
 <img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/191fe576-2a92-4e7d-b382-ae0d8437aa49" />

dan di sisi sebelah kanan ada foto profil yang bisa di geser dengan mengklik tanda panah kiri dan kanan.

Hero menggunakan Vue JS untuk mengatur pergantian gambar secara dinamis.

## 3. About Me Section

Section About Me adalah section kedua yang akan dilihat oleh pengguna ketika mengscroll website dan section ini berisi informasi singkat tentang diri saya.

<img width="1885" height="688" alt="image" src="https://github.com/user-attachments/assets/cb9029dd-a063-4f82-9c63-536220154080" />

Gambar diatas menampilkan paragraf deskripsi dan ada pula divider dekoratif sebagai pemisah antara paragraf dan cards dibawahnya.

<img width="1882" height="776" alt="image" src="https://github.com/user-attachments/assets/25b6add2-41c4-4690-a12e-f61341a2f35a" />

Gambar selanjutnya ini adalah tampilan cards dari My Skills dengan progress bar yang dibuat menggunakan Bootstrap dan dikontrol melalui data Vue JS, serta card Experience yang berisi daftar pengalaman.

## 4. Certificates Section

<img width="1888" height="663" alt="image" src="https://github.com/user-attachments/assets/f6824acb-81c8-42d4-b603-3098b54aec74" />

<img width="1882" height="778" alt="image" src="https://github.com/user-attachments/assets/65b4efdd-65b9-4b2d-8f89-c6d687cc84c3" />

Section sertifikat ini menampilkan daftar beberapa sertifikat dalam bentuk card/grid layout. Dibagi lagi menjadi dua kategori, yaitu Competition yang berisi sertifikat pertandingan atau perlombaan, serta kategori Leadership & Events yang berisi sertifikat dari mengikut event atau berpartisipasi dalam suatu kegiatan.

 <img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/67a305d8-c504-44c9-b720-c953ad9cccad" /> 

Setiap card memiliki tombol "Show" yang akan menampilkan detail sertifikat dalam bentukk modal popup.

Data sertifikat disimpan secara statis di dalam Vue JS (array of objects).

## 5. Modal Popup

<img width="1882" height="870" alt="image" src="https://github.com/user-attachments/assets/c36033f7-5454-4c1e-b99c-474c24edc3b9" />

Fitur modal popup ini digunakan untuk menampilkan gambar sertifikat, judul, dan deskripsi detailnya.

Modal menggunakan Bootstrap 5 dan juga dengan CSS agar mempercantik tampilan (blur background, animasi, dan custom close button).

## 6. Journal Section

<img width="1883" height="407" alt="image" src="https://github.com/user-attachments/assets/c66be362-d6ab-4f20-98cc-5174db3cffc7" />

<img width="1882" height="778" alt="image" src="https://github.com/user-attachments/assets/ccfb6152-a46e-4381-8505-f28451f54c22" />

Section journal adalah section yang menampilkan beberapa hasil journaling dalam bentuk grid.

Fitur-fitur nya yaitu ada layout 3 kolom yang responsive, lalu ada Hover animation pada card nya, dan juga ada divider dekoratif untuk pemisah untuk mempercantik tampilan.

## 7. Footer

<img width="1883" height="175" alt="image" src="https://github.com/user-attachments/assets/81d65b8c-2747-4200-9f1e-32cb8ffdd17e" />


# Penjelasan Code Setiap Section/Fitur

<nav class="navbar navbar-expand-lg fixed-top custom-navbar">
    <div class="container">
        <a class="navbar-brand brand-text" href="#">Lalaa</a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">About Me</a></li>
                <li class="nav-item"><a class="nav-link" href="#certificates">Certificates</a></li>
                <li class="nav-item"><a class="nav-link" href="#journal">Journal</a></li>
            </ul>
        </div>
    </div>
</nav>

# Teknologi yang Digunakan

## 1. HTML5

HTML5 digunakan untuk membangun struktur dasar website seperti section, navbar, card, dan modal.

## 2. CSS3

CSS3 digunakan dalam pembuatan website ini untuk styling tampilan website, termasuk warna, layout, animasi hover, efek shadow, serta desain feminine dan elegant.

## 3. Bootstrap 5

Framework CSS yang digunakan untuk mempermudah pembuatan layout responsive menggunakan grid system serta komponen seperti navbar dan modal.

## 4. Bootstrap Icons

Bootstrap icons digunakan untuk menampilkan ikon sosial media seperti Instagram, TikTok, dan Email di bagian footer agar lebih menarikk.

## 5. Vue JS 

Vue JS digunakan untuk membuat website lebih dinamis, seperti mengatur slider, gambar, menyimpan dan menampilkan data sertifikat, filter kategori, serta mengontrol modal popup di bagian sertifikat section.

## 6. Google Fonts (Playfair Display & Poppins)

Google fonts tentunya digunakan untuk mengganti fonts teks yang ada di dalam website agar lebih cantik tampilannya. Playfair Display digunakan untuk judul agar terlihat elegan, sedangkan Poppins digunakan untuk teks utama agar tetap stylish dan mudah ddibaca.
