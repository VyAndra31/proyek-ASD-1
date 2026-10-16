# Proyek Linked List - Algoritma dan Struktur Data

Proyek ini bertujuan untuk menambahkan dan mengimplementasikan fungsionalitas tambahan pada struktur data **Singly Linked List** dan **Doubly Linked List** sesuai dengan spesifikasi yang diberikan.

---

## 👥 Anggota Kelompok
* Livyandra Lita Halim, 255150200111009
* Faisya Anindya Shafah, 255150201111046
* Aisyah Zayyana Ghayda. DM, 255150200111001

---

## 📌 Deskripsi Fungsionalitas
Berikut adalah method-method yang diimplementasikan pada proyek ini:

1. **`public Object get(int index)`**  
   Mengembalikan data pada indeks ke-`i` dimulai dari `head` (indeks 0).
2. **`public int indexOf(Object targetData)`**  
   Mencari kemunculan pertama `targetData` pada linked list dan mengembalikan indeksnya. Jika tidak ditemukan, mengembalikan `-1`.
3. **`public void printReverse()`**  
   Mencetak data pada linked list dengan urutan terbalik, dari `tail` ke `head`.
4. **`public boolean remove(Object targetData)`**  
   Mencari dan menghapus node dengan data yang sesuai dengan `targetData`. Mengembalikan `true` jika berhasil, dan `false` jika data tidak ada.
5. **`public Object[] toArray()`**  
   Mengambil seluruh data node pada linked list dan menyusunnya secara berurutan ke dalam sebuah Array (dari `head` sampai `tail`).

---

## 📊 Pembagian Tugas

| Method | Singly Linked List | Doubly Linked List |
| :--- | :--- | :--- |
| `get(int index)` | Aisyah | Livyandra |
| `indexOf(Object targetData)` | Aisyah | Livyandra |
| `printReverse()` | Livyandra | Faisya |
| `remove(Object targetData)` | Aisyah | Faisya |
| `toArray()` | Faisya | Aisyah |

---

## ⚙️ Cara Menjalankan & Pengujian
Untuk memverifikasi bahwa seluruh implementasi berjalan dengan benar, jalankan file pengujian yang telah disediakan:
* `testSinglyLinkedList` untuk menguji fungsionalitas Singly Linked List.
* `testDoublyLinkedList` untuk menguji fungsionalitas Doubly Linked List.
