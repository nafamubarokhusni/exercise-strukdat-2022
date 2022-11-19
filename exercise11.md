Latihan Bab Linear Data Structure

1. Stacks, Queues , Deques
- Jelaskan pengertian Stack, Queues dan Deques dalam struktur data
- Jelaskan perbedaan antara Stack, Queues dan Deques

2. Linked Lists
- Jelaskan pengertian Linked Lists dalam struktur data
- Jelaskan perbedaan antara Single Linked List dengan Double Linked List
- Carilah deskripsi dan jelaskan contoh penerapan lain pada Linked List yaitu Circular Linked list
- Jelaskan perbedaan antara Single Linked List, Double Linked List dan Circular Linked List

3. Carilah deskripsi dan jelaskan salah satu contoh linear data structure yang lain, misalkan seperti Priority Queues / Maps / Hash Tables

4. Jelaskan kelebihan dan kekurangan dari Stacks, Queues , Deques, Single Linked List dan Double Linked List

Jawaban

1. Stacks, Queues , Deques
- Stack adalah kumpulan objek yang dimasukan dan dikeluarkan berdasarkan prinsip last-in, first-out (LIFO). Queues adalah kumpulan objek yang dimasukan dan dikeluarkan berdasarkan prinsip first-in, first-out (FIFO). Deques (double ended Queues) adalah struktur data yang mendukung memasukan data dan menghapus dari kedua sisi (depan dan belakang) yang biasanya di baja "deck"
- Perbedaan yang signifikan dari ketiga struktur data tersebut adalah dari urutan data yang dimasukan atau dihapus. Stack dengan prinsip LIFO-nya, Queues dengan prinsip FIFO-nya dan Deques yang dapat memasukan/menghapus data dari kedua arah

2. Linked Lists
- Linked List adalah sebuah struktur data yang digunakan untuk menyimpan sejumlah objek data biasanya secara terurut sehingga memungkinkan penambahan, pengurangan, dan pencarian atas elemen data yang tersimpan dalam node dilakukan secara lebih efektif
- Single linked list hanya memiliki 1 pointer yaitu next yang menunjuk ke node selanjutnya, Double linked list memiliki 2 pointer yaitu next dan prev yang menunjuk ke node selanjutnya dan sebelumnya
- Circular Linked list merupakan single linked list yang head dan tail-nya terhubung membentuk circular (lingkaran), salah satu penerapan circular linked list adalah game checkpoint yang finishnya kembali ke garis start,  Round-Robin Schedulers, dll
- Perbedaan signifikan dari ketiga jenis linked list tersebut adalah pada pointernya, dimana single linked list memiliki 1 pointer yaitu next, sedangkan double linked list memiliki 2 pointer yaitu next dan prev, lalu circular linked list merupakan single linked list yang pointer tailnya menunjuk ke node headnya.

3. 
- Priority Queues adalah tipe data abstrak yang mirip dengan Queue biasa di mana setiap elemen tambahan memiliki prioritas yang terkait dengannya. Dalam antrian prioritas, elemen dengan prioritas tinggi dilayani sebelum elemen dengan prioritas rendah.
- Maps atau Associative array adalah tipe data abstrak yang berisi kumpulan records. Setiap record dari map berisi sebuah key dan sebuah value.(mirip dictionary)
- Hash Map/Hash Table merupakan implementasi dari Map. Hash Table adalah struktur data yang mengimplementasikan array asosiatif atau dictionary yang memetakan kunci ke nilai.
4. 
Stacks
Kelebihan:
- Kelebihan stack yaitu penambahan dan penghapusan data dapat dilakukan dengan cepat, yaitu selama memori masih tersedia penambahan data bisa terus dilakukan
Kekurangan:
- Kekurangan stack yaitu setiap sel tidak hanya menyimpan value saja, melainkan juga pointer ke sel berikutnya. Hal ini menyebabkan implementasi stack memakai linked list akan memerlukan memori yang lebih banyak daripada di implementasikan dengan array
Queues
Kelebihan:
- Data dalam jumlah besar dapat dikelola secara efisien
Kekurangan:
- Operasi seperti penyisipan dan penghapusan elemen dari tengah cenderung banyak memakan waktu
Deques
Kelebihan:
- Data dapat di tambah/dihapus dari ke dua sisi
Kekurangan:
- memiliki kompleksitas yang cukup tinggi
Single Linked List
Kelebihan:
- penambahan data di belakang, hanya dibutuhkan tail yang mengikat node baru saja tanpa harus menggunakan perulangan pointer bantu
Kekurangan:
- Pemakaian memory lebih besar. Proses traversal lebih panjang karena tidak bisa langsung mengakses data dengan indeks. Tidak dapat melakukan reverse traversal
Double Linked List
Kelebihan:
- Dapat melakukan reverse tranversal
Kekurangan:
- Pemakaian memory lebih besar. Proses traversal lebih panjang karena tidak bisa langsung mengakses data dengan indeks.