# Laporan Praktikum 3: TEPI / AMBANG
## Ridho Chaerullah 202231122
### Deskripsi
Proyek ini merupakan bagian dari praktikum yang bertujuan untuk mempelajari konsep deteksi tepi dan ambang pada citra digital. Implementasi dilakukan menggunakan bahasa pemrograman Python dengan bantuan pustaka OpenCV dan Skimage.

### Isi Laporan
Notebook ini mencakup beberapa langkah utama dalam proses deteksi tepi dan ambang, yaitu:

Membaca dan menampilkan citra.
Memperkirakan nilai ambang manual.
Implementasi fungsi titeratif untuk deteksi tepi.
Langkah-langkah
Membaca dan Menampilkan Citra:

Menggunakan cv2.imread() untuk membaca citra.
Menampilkan citra menggunakan cv2.imshow().
Memperkirakan Nilai Ambang:

Menyalin citra asli.
Menggunakan nilai ambang yang ditentukan untuk memproses setiap piksel pada citra.
Fungsi Titeratif:

Menghitung rata-rata nilai piksel untuk dua kelompok berdasarkan nilai ambang awal.
Mengiterasi proses hingga nilai ambang konvergen.
### Library yang digunakan
OpenCV
NumPy
Matplotlib
Skimage