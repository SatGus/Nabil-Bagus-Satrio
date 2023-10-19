# Smart Glasses
Smart glasses diperuntukan sebagai alat bantu orang buta agar bisa juga merasakan dunia dengan kenikmatan melihat, termasuk kemampuan pendeteksian objek dan pengenalan wajah
Ada fitur-fitur yang sangat diunggulkan dari Smart Glasses yaitu:

Mendeteksi Objek: Smart Glasses bisa mendeteksi semua Objek di sekitar dengan media suara atau getaran.

Pengenalan Wajah: Pengenalan wajah tidak kalah penting agar pengguna bisa mengenali orang yang mereka temui dengan bantuan suara atau perangkat pendengaran. Ini dapat membantu dalam interaksi sosial dan mengenali teman dan keluarga.

Sebagai Navigasi: Smart glasses dapat memberikan petunjuk arah, sangat membantu dalam bergerak di sekitar lingkungan.

Sebagai pembantu Baca Teks: Smart glasses dapat membaca teks yang ada di sekitar pengguna, seperti tanda-tanda jalan, buku, atau layar perangkat elektronik.

Konektivitas sosial: Koneksi ke internet dan perangkat cerdas lainnya memungkinkan pengguna untuk mengakses informasi tambahan, seperti cuaca, berita, atau penunjuk jalan yang lebih canggih.

Cara Kerja Dari Smart Glasses
Langkah pertama: Pengguna (buta) akan mengklik tombol.
Langkah kedua: kamera mengambil gambar ketika pengguna melakukan suatu tindakan” mengklik tombol “, kemudian mikrokontroler menerima gambar dari kamera dan mengirimkannya kembali ke “cloud”.
Langkah ketiga: Setelah cloud memuat model, cloud menormalkan input gambar: Normalisasi data adalah langkah penting yang memastikan bahwa setiap parameter input (piksel, dalam hal ini) memiliki distribusi data yang serupa. Hal ini membuat konvergensi lebih cepat saat melatih jaringan. Normalisasi data dilakukan dengan mengurangkan mean dari setiap piksel, kemudian membagi hasilnya dengan standar deviasi. Distribusi data tersebut akan menyerupai kurva Gaussian yang berpusat pada nol. Untuk masukan gambar, kita memerlukan angka piksel positif, sehingga kita dapat memilih untuk menskalakan data yang dinormalisasi dalam rentang [0,1] atau [0, 255]. Untuk contoh kumpulan data kita, montase berikut mewakili data yang dinormalisasi.>>Kemudian Kenali wajah & deteksi objek.>>Akhirnya kirim output ke mikrokontroler.
Langkah keempat: mikrokontroler mengubah keluaran “teks” menjadi suara ketika menerimanya dari “cloud”. “Suara ini akan menjadi keluaran bagi pengguna, ini lebih banyak fleksibilitas bagi pengguna.” 
