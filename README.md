# Deteksi_Daun-PC_202231011_DEWISAFITRI_B
# Teori yang mendukung

## Deteksi daun
Deteksi daun dalam pengolahan citra digital merupakan proses identifikasi dan ekstraksi area yang dianggap sebagai daun dari sebuah gambar digital. 
Proses ini memiliki berbagai aplikasi, termasuk dalam bidang pertanian, botani, dan lingkungan untuk pemantauan kesehatan tanaman, klasifikasi jenis tanaman, dan studi perubahan iklim.
Deteksi daun adalah proses pengenalan dan pengidentifikasian daun pada suatu gambar atau citra. Teknik ini digunakan dalam berbagai aplikasi, seperti:

1. **Agricultural monitoring**: untuk memantau kesehatan dan kondisi tanaman.  
2. **Plant disease detection**: untuk mendeteksi penyakit pada daun.  
3. **Leaf classification**: untuk mengklasifikasikan jenis daun berbeda.   
4. **Robotics and computer vision**: untuk mengembangkan sistem visi komputer yang dapat mengenali dan memproses daun.

Teknik deteksi daun dapat dibagi menjadi beberapa tahap:

1. **Image acquisition**: mengambil gambar daun menggunakan kamera atau sensor lainnya.  
2. **Image preprocessing**: memproses gambar untuk meningkatkan kualitas dan menghilangkan noise.  
3. **Feature extraction:** mengekstrak fitur-fitur dari daun, seperti bentuk, ukuran, warna, dan tekstur.  
4. **Classification**: mengklasifikasikan daun berdasarkan fitur-fitur yang diekstrak.

Beberapa teknik yang digunakan dalam deteksi daun adalah:

1. **Color-based segmentation**: menggunakan warna untuk memisahkan daun dari latar belakang.  
2. **Edge detection**: menggunakan deteksi tepi untuk menemukan kontur daun.  
3. **Shape analysis**: menggunakan analisis bentuk untuk mengidentifikasi daun.  
4. **Texture analysis**: menggunakan analisis tekstur untuk mengidentifikasi daun.  
5. **Machine learning**: menggunakan algoritma machine learning, seperti neural networks atau support vector machines, untuk mengklasifikasikan daun.


## OpenCV

OpenCV (Open Source Computer Vision Library) adalah sebuah perpustakaan komputer yang digunakan untuk pengolahan citra dan pengenalan pola. 
Perpustakaan ini dikembangkan oleh Intel dan sekarang dikelola oleh perusahaan independen yang bernama Itseez.

### Fitur OpenCV

OpenCV memiliki banyak fitur yang berguna untuk pengolahan citra dan pengenalan pola, antara lain:

1. Pengolahan citra: OpenCV dapat melakukan operasi pengolahan citra seperti konversi format, resize, crop, flip, dan lain-lain.  
2. Deteksi wajah: OpenCV dapat mendeteksi wajah manusia dalam sebuah citra.  
3. Pengenalan pola: OpenCV dapat mengenali pola dalam sebuah citra, seperti bentuk, warna, dan tekstur.  
4. Pengolahan video: OpenCV dapat melakukan operasi pengolahan video seperti capture, playback, dan analisis.  
5. Machine learning: OpenCV memiliki fitur machine learning yang dapat digunakan untuk klasifikasi, regresi, dan clustering.

### Fungsi-fungsi OpenCV

Berikut adalah beberapa fungsi OpenCV yang sering digunakan:

1. cv2.imread(): Membaca citra dari file.  
2. cv2.imshow(): Menampilkan citra.  
3. cv2.cvtColor(): Mengkonversi format citra.  
4. cv2.resize(): Mengubah ukuran citra.  
5. cv2.threshold(): Mengaplikasikan thresholding pada citra.  
6. cv2.inRange(): Mendeteksi piksel dalam rentang warna tertentu.  
7. cv2.bitwise_and(): Melakukan operasi bitwise AND pada dua citra.

## NumPy

NumPy (Numerical Python) adalah sebuah library Python yang digunakan untuk mengolah data numerik dan array multidimensi. 
NumPy memungkinkan kita untuk melakukan operasi matematika dan statistik pada data dengan cepat dan efisien.

### Fitur NumPy
NumPy memiliki beberapa fitur yang berguna, antara lain:

1. Array multidimensi: NumPy memungkinkan kita untuk membuat array dengan jumlah dimensi yang tidak terbatas.  
2. Operasi matematika: NumPy mendukung operasi matematika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian pada array.  
3. Operasi statistik: NumPy memiliki fungsi untuk menghitung statistik seperti mean, median, mode, dan standar deviasi.  
4. Manipulasi data: NumPy memungkinkan kita untuk melakukan operasi seperti sorting, filtering, dan grouping pada data.  

### Fungsi-fungsi NumPy
Berikut adalah beberapa fungsi NumPy yang sering digunakan:

1. numpy.array(): Membuat array dari data.  
2. numpy.zeros(): Membuat array dengan nilai nol.  
3. numpy.ones(): Membuat array dengan nilai satu.  
4. numpy.random.rand(): Membuat array dengan nilai acak.  
5. numpy.mean(): Menghitung mean dari array.  
6. numpy.median(): Menghitung median dari array.  
7. numpy.std(): Menghitung standar deviasi dari array.


## Matplotlib

Matplotlib adalah sebuah library Python yang digunakan untuk membuat grafik dan visualisasi data. 
Matplotlib memungkinkan kita untuk membuat berbagai jenis grafik, seperti plot 2D, plot 3D, histogram, scatter plot, dan lain-lain.

### Fitur Matplotlib
Matplotlib memiliki beberapa fitur yang berguna, antara lain:

1. Membuat grafik 2D dan 3D  
2. Membuat histogram dan scatter plot  
3. Membuat plot bar dan pie chart  
4. Membuat plot kontur dan surface plot  
5. Membuat animasi grafik  
6. Membuat grafik interaktif  
7. Mendukung berbagai format file output, seperti PNG, PDF, EPS, dan lain-lain  

### Fungsi-fungsi Matplotlib
Berikut adalah beberapa fungsi Matplotlib yang sering digunakan:

1. matplotlib.pyplot.plot(): Membuat plot 2D sederhana  
2. matplotlib.pyplot.scatter(): Membuat scatter plot  
3. matplotlib.pyplot.bar(): Membuat plot bar  
4. matplotlib.pyplot.hist(): Membuat histogram  
5. matplotlib.pyplot.imshow(): Membuat plot image  
6. matplotlib.pyplot.contour(): Membuat plot kontur  
7. matplotlib.pyplot.surface(): Membuat plot surface

## Segmentasi dalam Deteksi Daun

Segmentasi adalah proses pemisahan objek dari latar belakang dalam sebuah gambar.   
Dalam konteks deteksi daun, segmentasi digunakan untuk memisahkan daun dari latar belakang, seperti tanah, batang, atau lainnya.

### Tujuan Segmentasi
Tujuan segmentasi dalam deteksi daun adalah untuk:

1. Mengidentifikasi daun dalam gambar  
2. Memisahkan daun dari latar belakang  
3. Menghitung karakteristik daun, seperti ukuran, bentuk, dan warna  

### Proses Segmentasi
Proses segmentasi dalam deteksi daun melibatkan beberapa tahap, yaitu:

1. Pre-processing: Gambar diolah untuk meningkatkan kualitas dan mengurangi noise.  
2. Thresholding: Gambar diubah menjadi biner, yaitu hanya terdiri dari dua nilai, 0 dan 255. Nilai 0 untuk latar belakang dan 255 untuk objek (daun).  
3. Edge detection: Tepi daun diidentifikasi menggunakan algoritma seperti Canny atau Sobel.  
4. Region growing: Daun diidentifikasi berdasarkan karakteristik seperti warna, tekstur, dan bentuk.  
5. Post-processing: Hasil segmentasi diolah untuk menghilangkan noise dan meningkatkan akurasi.  

# Penjelasan singkat mengenai program deteksi daun 
## Segmentasi Buah dan Daun menggunakan OpenCV dan Matplotlib

Program ini adalah sebuah skrip Python yang menggunakan library OpenCV dan Matplotlib untuk memisahkan buah dan daun dari sebuah gambar. 
Program ini mengambil gambar buah (dalam hal ini, jambu) sebagai input dan menghasilkan empat gambar:

1. Gambar asli: Gambar ini adalah gambar awal yang diambil sebagai input oleh program.  
2. Mask buah: Gambar ini menunjukkan area buah pada gambar asli. Area buah ditandai dengan warna putih, sedangkan area lainnya ditandai dengan warna hitam.  
3. Segmentasi buah: Gambar ini menunjukkan hasil pemisahan buah dari gambar asli. Hanya area buah yang terlihat pada gambar ini.  
4. Segmentasi daun: Gambar ini menunjukkan hasil pemisahan daun dari gambar asli. Hanya area daun yang terlihat pada gambar ini.  

 ## Program ini menggunakan teknik pemrosesan citra untuk memisahkan buah dan daun dari gambar asli. Teknik ini melibatkan beberapa langkah, yaitu:
 
1. Mengkonversi gambar dari ruang warna BGR (Blue, Green, Red) ke ruang warna RGB (Red, Green, Blue)  
2. Mengkonversi gambar dari ruang warna RGB ke ruang warna HSV (Hue, Saturation, Value)  
3. Menentukan range warna untuk buah dan daun  
4. Membuat mask untuk buah dan daun menggunakan range warna yang telah ditentukan  
5. Melakukan operasi bitwise AND untuk memisahkan buah dan daun dari gambar asli  

Program ini sangat berguna dalam berbagai aplikasi, seperti pengolahan citra, pengenalan pola, dan robotika. 
Dengan menggunakan program ini, kita dapat memisahkan buah dan daun dari gambar asli dan melakukan analisis lebih lanjut pada hasil segmentasi.

# Tahapan cara menyelesaikan project secara rinci
## 1. Impor Library dan Membaca Gambar

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/509cbb42-f7d6-4e6d-844f-65e4fe721351)  
Penjelasan : Bagian ini dari program mengimpor library yang diperlukan, termasuk OpenCV (cv2), NumPy (np), dan Matplotlib (matplotlib.pyplot sebagai plt).   Kemudian, program membaca gambar dari file jambu.jpg menggunakan fungsi imread dari OpenCV dan menyimpannya dalam variabel image.

## 2. Konversi Gambar ke RGB dan HSV

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/dfc4617a-cbff-4359-93ac-0e47bbde4f1e)  
Penjelasan: Bagian ini dari program mengkonversi gambar dari format BGR (Biru, Hijau, Merah) ke format RGB (Merah, Hijau, Biru) menggunakan fungsi cvtColor dari OpenCV. Hasil konversi disimpan dalam variabel image_rgb. Kemudian, program mengkonversi gambar ke format HSV (Hue, Saturation, Value) menggunakan fungsi cvtColor lagi. Hasil konversi disimpan dalam variabel hsv.


## 3. Deteksi Warna Jambu

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/e77ce1de-b005-4372-9bc0-90cf2cfca301)  
Penjelasan: Bagian ini dari program mendefinisikan batas bawah dan atas untuk warna coklat menggunakan array NumPy lower_brown dan upper_brown. Kemudian, program menggunakan fungsi inRange dari OpenCV untuk mendeteksi piksel dalam gambar HSV yang berada dalam rentang warna coklat. Hasil deteksi disimpan dalam variabel mask_fruit.

## 4. Segmentasi Jambu

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/14394a75-cc8d-4f03-9da5-acc5fbc61f5d)  
Penjelasan: Bagian ini dari program melakukan operasi bitwise AND antara gambar RGB asli dan dirinya sendiri, menggunakan mask mask_fruit untuk memilih hanya piksel yang sesuai dengan jambu. Hasil segmentasi disimpan dalam variabel segmented_fruit.

## 5. Deteksi Warna Daun

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/c75a523f-5457-4026-b2c7-090a859aa156)  
Penjelasan: Bagian ini dari program mendefinisikan batas bawah dan atas untuk warna hijau menggunakan array NumPy lower_green dan upper_green. Kemudian, program menggunakan fungsi inRange dari OpenCV untuk mendeteksi piksel dalam gambar HSV yang berada dalam rentang warna hijau. Hasil deteksi disimpan dalam variabel mask_leaf.

## 6. Segmentasi Daun

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/d843a386-032b-4bb7-9c9f-c63dc0757211)  
Penjelasan: Bagian ini dari program melakukan operasi bitwise AND antara gambar RGB asli dan dirinya sendiri, menggunakan mask mask_leaf untuk memilih hanya piksel yang sesuai dengan daun. Hasil segmentasi disimpan dalam variabel segmented_leaf.

## 7. Menampilkan Gambar dan Hasil Segmentasi

![image](https://github.com/dsftri/Deteksi_Daun-PC_202231011_DEWISAFITRI_B/assets/169512705/e016a1b9-e834-4ada-988c-c8472527359b)  
Penjelasan:
Program ini menggunakan library Matplotlib untuk menampilkan gambar dan hasil segmentasi. Program ini terdiri dari beberapa bagian:

1. Membuat figure dengan ukuran 20x20 inch menggunakan plt.figure(figsize=(20, 20)).  
2. Membuat subplot dengan ukuran 2x2 menggunakan plt.subplot(2, 2, 1), plt.subplot(2, 2, 2), plt.subplot(2, 2, 3), dan plt.subplot(2, 2, 4).  
3. Menampilkan gambar asli menggunakan plt.imshow(image_rgb) pada subplot pertama.  
4. Menampilkan mask jambu menggunakan plt.imshow(mask_fruit, cmap='gray') pada subplot kedua.  
5. Menampilkan hasil segmentasi jambu menggunakan plt.imshow(segmented_fruit) pada subplot ketiga.  
6. Menampilkan hasil segmentasi daun menggunakan plt.imshow(segmented_leaf) pada subplot keempat.  
7. Menambahkan judul pada setiap subplot menggunakan plt.title().  
8. Menampilkan axis pada setiap subplot menggunakan plt.axis('on').  
9. Menampilkan semua subplot menggunakan plt.show().
