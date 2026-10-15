# Sistem Pengelolaan Perpustakaan

Program sederhana berbasis C# yang menerapkan konsep **Object-Oriented Programming (OOP)** untuk merepresentasikan berbagai jenis koleksi perpustakaan, seperti buku, novel, komik, dan majalah.


## Konsep OOP yang Digunakan

- **Class and Object** — Membuat class untuk merepresentasikan item perpustakaan dan objek dari setiap jenis item.
- **Constructor** — Menginisialisasi atribut objek saat dibuat.
- **Inheritance** — Menggunakan pewarisan, seperti `novel` dan `komik` yang mewarisi class `buku`.
- **Method Overriding** — Menyesuaikan implementasi method `deskripsi()` pada setiap subclass.
- **Polymorphism** — Menyimpan berbagai jenis item dalam satu koleksi bertipe `List<item>` dan memanggil method `deskripsi()` sesuai jenis objeknya.
- **Encapsulation** — Menggunakan atribut `private` pada koleksi di class `Perpustakaan` untuk membatasi akses langsung dari luar class.


## Tujuan Pembelajaran

Proyek ini dibuat sebagai langkah dalam mengerjakan tugas Praktkum OOP, serta sebagai latihan untuk menerapkan konsep-konsep di OOP seperti pewarisan, overriding, dan polymorphism.
