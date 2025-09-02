# Java-Collection-Concept

# Sistem Pengelolaan Buku Perpustakaan

Membuat sistem pengelolaan buku di perpustakaan. Sistem ini mencatat daftar buku, memungkinkan pengguna untuk menambahkan buku baru, mencari buku berdasarkan judul, dan menghapus buku dari daftar.
  1. Kelas Book: Representasi sebuah buku dengan atribut:
    a. String title
    b. String author
    c. String ISBN
  2. Kelas Library: Mengelola koleksi buku menggunakan ArrayList Book dengan metode:
    a. addBook(Book book): Menambahkan buku.
    b. removeBook(String ISBN): Menghapus buku berdasarkan ISBN.
    c. findBooksByTitle(String title): Mencari buku berdasarkan judul.
  3. Data diinputkan secara statis
  4. Data minimal 5 buku yang diinputkan/di deklarasikan dalam program
  5. Proses yang dilakukan dalam program : tambah, hapus, cari

  Gambaran output program :
    All books in the library:
    Title: Java Programming, Author: John Doe, ISBN: 12345
    Title: OOP in Java, Author: Jane Smith, ISBN: 67890
    Title: Java Programming, Author: Emily Davis, ISBN: 11223
    Searching for books with title 'Java Programming':
    Title: Java Programming, Author: John Doe, ISBN: 12345
    Title: Java Programming, Author: Emily Davis, ISBN: 11223
    Removing book with ISBN '12345'
    Title: OOP in Java, Author: Jane Smith, ISBN: 67890
    Title: Java Programming, Author: Emily Davis, ISBN: 11223
