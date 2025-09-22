# PBO_Posttest3

# Menerapkan encapsulation (getter dan setter)

<img width="538" height="688" alt="Screenshot 2025-09-22 150410" src="https://github.com/user-attachments/assets/8a06db8b-fa60-4b84-ac16-a8c048fa9dd5" />

- Getter digunakan untuk mengambil nilai dari atribut (misalnya getNama(), getStok(), getSatuan(), getKadaluarsa()).
Contoh: getNama() mengembalikan nilai dari variabel nama.

- Setter digunakan untuk mengubah atau mengisi nilai atribut (misalnya setNama(), setStok(), setSatuan(), setKadaluarsa()).
Contoh: setStok(int stok) mengisi nilai variabel stok.


# Menerapkan inheritance (1 superclass dengan 2 subclass)


# Superclass Bahan.java
- Properties ini digunakan untuk menyimpan data dari setiap bahan inventaris (nama bahan, jumlah stok, satuan, dan tanggal kadaluarsa). Karena dibuat dengan private, maka data hanya bisa diakses melalui getter & setter, bukan langsung dari luar class
- Constructor Fungsinya untuk menginisialisasi objek baru dengan data yang langsung lengkap (nama, stok, satuan, kadaluarsa)
- Getter digunakan untuk mengambil nilai dari atribut (misalnya getNama(), getStok(), getSatuan(), getKadaluarsa()). Contoh: getNama() mengembalikan nilai dari variabel nama.
- Setter digunakan untuk mengubah atau mengisi nilai atribut (misalnya setNama(), setStok(), setSatuan(), setKadaluarsa()). Contoh: setStok(int stok) mengisi nilai variabel stok.
- Method info() mengembalikan informasi lengkap dalam bentuk string yang sudah diformat rapi menggunakan String.format. Formatnya menampilkan nama, stok, satuan, dan kadaluarsa dalam bentuk tabel berkolom.


<img width="728" height="849" alt="image" src="https://github.com/user-attachments/assets/ff932a32-f15f-46bb-9605-b5a4ef79fc90" />
<img width="727" height="102" alt="image" src="https://github.com/user-attachments/assets/c81f00f0-5473-4a82-b853-06a46a5dfdfb" />


- Subclass BahanInstant.java
<img width="841" height="431" alt="image" src="https://github.com/user-attachments/assets/ec305dc8-e698-4882-9e60-91564fd63cb6" />



- Subclass BahanMinuman.java
<img width="907" height="431" alt="image" src="https://github.com/user-attachments/assets/247af3d2-5e3f-411f-80d5-20f43ef7f931" />
