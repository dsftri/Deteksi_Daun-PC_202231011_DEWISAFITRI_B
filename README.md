# Deteksi_Daun-PC_202231011_DEWISAFITRI_B
## Teori yang mendukung
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
