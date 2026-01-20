# TUGAS_GUI_KALKULATOR_12
# Aplikasi Kalkulator Desktop Java (Swing)

Repository ini berisi source code aplikasi **kalkulator desktop** berbasis **Java Swing**. Aplikasi ini dirancang untuk melakukan operasi aritmatika dasar dengan antarmuka grafis (GUI) sederhana dan mudah digunakan.

## Deskripsi Aplikasi
Aplikasi kalkulator ini memungkinkan pengguna melakukan perhitungan matematika dasar seperti penjumlahan, pengurangan, perkalian, pembagian, dan operasi modulus. Antarmuka dibuat menggunakan **Java Swing** dengan tata letak **BorderLayout** dan **GridLayout** agar tampilan tombol rapi dan terstruktur.

## Fitur
- Operasi aritmatika dasar:
  - Penjumlahan (+)
  - Pengurangan (-)
  - Perkalian (*)
  - Pembagian (/)
  - Modulus (% / Mod)
- Tampilan GUI berbasis Java Swing
- Input angka melalui tombol
- Tombol keluar (Exit)
- Penanganan error input dasar
- Tampilan hasil otomatis di text field

## Teknologi yang Digunakan
- Java
- Java Swing (JFrame, JButton, JTextField, JPanel)
- AWT Layout Manager (BorderLayout, GridLayout)

## Struktur Program
- `KalkulatorLayout`
  - Merupakan class utama yang mewarisi `JFrame`
  - Mengatur tampilan window dan komponen GUI
  - Mengelola logika perhitungan
- `main()`
  - Menjalankan aplikasi menggunakan `SwingUtilities.invokeLater`

## Cara Kerja Aplikasi
1. Pengguna memasukkan angka melalui tombol.
2. Pengguna memilih operator matematika.
3. Pengguna memasukkan angka kedua.
4. Tombol `=` ditekan untuk menampilkan hasil.
5. Tombol `Exit` digunakan untuk menutup aplikasi.

## Contoh Operasi
- Input: 8 + 4  
  Output: 12

- Input: 10 / 2  
  Output: 5

- Input: 10 Mod 3  
  Output: 1

## Tujuan Pengembangan
- Mempelajari konsep GUI pada Java
- Memahami penggunaan Java Swing
- Mengimplementasikan event handling pada aplikasi desktop
- Mengasah logika pemrograman berorientasi objek (OOP)

## Cara Menjalankan Program
1. Pastikan Java Development Kit (JDK) sudah terpasang.
2. Compile program:
   ```bash
   javac KalkulatorLayout.java
