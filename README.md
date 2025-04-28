# Remedial-Perbaikan-Tugas-5-B

Praktikum ini bertujuan untuk membuat program **Kalkulator Bangun Ruang Mini** menggunakan konsep **pemrograman berorientasi objek (OOP)**. Program ini menghitung **volume** dan **berat** dua bangun ruang: **Kerucut** dan **Balok**. Program memanfaatkan konsep **interface**, **inheritance**, dan **polymorphism** dalam Java.

---

### **Deskripsi Program**
Program ini menyediakan menu dengan pilihan:
1. **Kerucut**: Menghitung volume dan berat kerucut.
2. **Balok**: Menghitung volume dan berat balok.
3. **Keluar**: Menyelesaikan program.

Jika memilih pilihan yang tidak valid, program akan memberi pesan kesalahan dan meminta pengguna untuk mencoba lagi.

---

### **Struktur Program**
Program ini terdiri dari beberapa class yang terpisah sesuai dengan fungsinya:
- **`HitungRuang` (Interface)**: Mendeklarasikan metode untuk menghitung volume dan berat.
- **`BangunRuang` (Abstract Class)**: Menyimpan atribut **nama** dan **massa**, serta mendeklarasikan metode **printInfo()**.
- **`Kerucut` dan `Balok` (Subclass)**: Mengimplementasikan **HitungRuang** untuk menghitung volume dan berat.
- **`KalkulatorBangunRuangMini` (Main Program)**: Menyediakan antarmuka pengguna dengan menu interaktif.

---

### **Cara Kerja Program**
Program menggunakan **perulangan while** untuk menampilkan menu:
1. **Pilihan 1**: Input data untuk **Kerucut**, lalu tampilkan volume, berat, dan garis pelukis.
2. **Pilihan 2**: Input data untuk **Balok**, lalu tampilkan volume dan berat.
3. **Pilihan 3**: Program selesai.
4. **Pilihan tidak valid**: Program meminta pengguna untuk mencoba lagi.

---

### **Penerapan OOP**
- **Abstraction**: Program menyembunyikan perhitungan dalam class **Kerucut** dan **Balok**.
- **Encapsulation**: Data seperti radius, panjang, dan massa disembunyikan dengan atribut private.
- **Inheritance**: **Kerucut** dan **Balok** mewarisi class **BangunRuang**.
- **Polymorphism**: Metode **printInfo()**, **hitungVolume()**, dan **hitungBerat()** diimplementasikan di subclass.

---

### **Hasil Pengujian**
Program berjalan sesuai dengan input pengguna. Misalnya:
```
Pilihan:
1. Kerucut
2. Balok
3. Keluar
Pilihan Anda: 1
Isikan nama: Kerucut
Isikan radius: 7
Isikan tinggi: 14
Isikan massa: 5
```

Output:
```
=============================================
Kerucut
=============================================
Volume          : 539.33
Berat           : 50.0
Garis pelukis   : 14.28
=============================================
```

---

### **Kesimpulan**
Program berhasil mengimplementasikan perhitungan volume dan berat bangun ruang menggunakan konsep OOP. Dengan perulangan menu dan validasi input, program mudah digunakan dan fleksibel untuk ditambah jenis bangun ruang lainnya.

---
