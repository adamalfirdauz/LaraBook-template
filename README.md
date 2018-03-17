# LaraBook template

LaraBook merupakan sebuah platform media sosial sederhana yang dibangun menggunakan laravel dan template bootstrap AdminLTE.

# Fitur

  - Buat status
  - Like
  - Comment

# Cara menggunakan
Repository ini hanya mengandung template, silahkan clone atau download sebagai zip.
1. Clone langsung di direktori projek.
    ```sh
    $ cd directory-project-anda/
    $ git clone https://github.com/adamalfirdauz/LaraBook-template.git
    ```
2. Ikuti workshop bagian blade templating laravel.

# Petunjuk atau syntax yang biasa digunakan.
1. Pembuatan layout
    - Untuk menggabungkan kodingan dari file yang berbeda.
        ```sh
         @include('something')
        ```
    - Untuk menyediakan bagian yang kemudian akan diisi oleh kode dinamis.
        ```sh
         @yield('content')
        ```
2. Penggunaan layout
    - Untuk meng-extend layout yang telah dibuat
        ```sh
         @yield('content')
        ```
    - Untuk mengisi yield
        ```sh
         @section('content')
          //some code here
         @endsection
        ```
# Repository Utama
- LaraBook ([Source](https://github.com/adamalfirdauz/LaraBook))

Writed by Adam Firdaus
[CodePanda](https://codepanda.web.id) &copy; 