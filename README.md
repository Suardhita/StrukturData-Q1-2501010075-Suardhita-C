1. Array memiliki akses data O(1) karena disimpan secara kontinu di memori, sedangkan Singly Linked List membutuhkan O(n) karena node tersimpan tidak berurutan sehingga harus ditelusuri satu per satu.
2. Linked List lebih efisien untuk operasi insert dan delete karena hanya mengubah pointer tanpa perlu menggeser elemen seperti pada Array.
3. Doubly Linked List memiliki dua pointer (prev dan next) yang membuat traversal dua arah lebih fleksibel namun membutuhkan memori lebih besar dibanding Singly Linked List.
4. Circular Linked List menghubungkan node terakhir ke node pertama sehingga membentuk siklus yang cocok untuk kasus seperti round-robin scheduling.
5. Array dinamis di Python akan melakukan resize dengan membuat array baru yang lebih besar dan menyalin data lama saat kapasitas penuh, sehingga operasi append tetap rata-rata O(1).
