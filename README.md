### 1. **DFD (Data Flow Diagram)**

**Pengertian:**
DFD adalah diagram yang menggambarkan aliran data dalam suatu sistem, dari sumber data (external entity) ke sistem, proses-proses yang mengolah data, penyimpanan data (data store), dan keluaran data.

**Fungsi:**

* Memodelkan alur data dan proses bisnis dalam sistem.
* Tidak fokus pada implementasi teknis (non-algoritmik), melainkan pada logika sistem.

**Simbol utama:**

* **Proses** (lingkaran atau oval)
* **Data Flow** (panah)
* **Data Store** (garis ganda atau persegi panjang terbuka)
* **External Entity** (persegi panjang)



### 2. **ERD (Entity Relationship Diagram)**

**Pengertian:**
ERD adalah diagram yang digunakan untuk memodelkan struktur data dan hubungan antar entitas dalam sistem basis data.

**Fungsi:**

* Mendeskripsikan hubungan antar tabel dalam database relasional.
* Menentukan atribut, primary key, dan foreign key.

**Komponen utama:**

* **Entitas** (persegi panjang)
* **Atribut** (elips)
* **Relasi** (belah ketupat)
* **Garis hubungan** antara entitas dan atribut/relasi



### 3. **Activity Diagram**

**Pengertian:**
Activity Diagram menggambarkan alur aktivitas (workflow) atau proses bisnis dari suatu sistem, termasuk urutan aktivitas, kondisi, dan percabangan.

**Fungsi:**

* Menjelaskan logika proses bisnis atau algoritma.
* Memperlihatkan aktivitas secara paralel atau berurutan.

**Simbol penting:**

* **Initial Node** (titik awal, bulat hitam)
* **Activity/Action** (persegi panjang dengan sudut tumpul)
* **Decision** (belah ketupat)
* **Final Node** (lingkaran dengan titik di dalamnya)



### 4. **Use Case Diagram**

**Pengertian:**
Use Case Diagram menggambarkan interaksi antara aktor (pengguna atau sistem eksternal) dan sistem, melalui skenario penggunaan (use case).

**Fungsi:**

* Mengidentifikasi fungsi-fungsi utama sistem dari sudut pandang pengguna.
* Menjadi dasar awal dalam perancangan sistem.

**Komponen utama:**

* **Aktor** (stick figure)
* **Use Case** (elips)
* **Hubungan** seperti association, include, extend
* **Boundary sistem** (kotak besar yang membungkus use case)



### 5. **Class Diagram**

**Pengertian:**
Class Diagram menggambarkan struktur sistem dalam bentuk kelas-kelas, atribut, metode (fungsi), serta hubungan antar kelas (asosisasi, pewarisan, dsb.).

**Fungsi:**

* Merepresentasikan desain sistem berorientasi objek.
* Menjadi blueprint untuk coding dalam OOP (Object Oriented Programming).

**Komponen utama:**

* **Class** (persegi panjang dengan 3 bagian: nama, atribut, metode)
* **Relasi antar kelas** (inheritance, association, aggregation, composition)



### 6. **Sequence Diagram**

**Pengertian:**
Sequence Diagram menunjukkan interaksi antar objek/kelas dalam urutan waktu tertentu, menggambarkan bagaimana pesan dikirim dari satu objek ke objek lain untuk menyelesaikan suatu proses.

**Fungsi:**

* Menjelaskan urutan eksekusi fungsi atau metode dalam skenario sistem.
* Digunakan untuk memvalidasi logika alur sistem.

**Elemen penting:**

* **Objek** (kotak di atas dengan nama)
* **Lifeline** (garis vertikal di bawah objek)
* **Pesan/Message** (panah horisontal)
* **Activation** (batang tipis vertikal pada lifeline saat objek aktif)

