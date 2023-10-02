<br>Nama : LeonHoss Hutagaol <br/>
<br>NPM  : 200810102151<br/>
<br>kelas: Riset Informatika D

# <h2>Topik : Pengolahan Citra Digital (Plat Nomor) Dengan Robert Filter dan Framing Image<h2/>

# <h3>Riset : Sistem Identifikasi Plat Nomor Kendaraan Menggunakan Metode Robert Filter
dan Framing Image Berbasis Pengolahan Citra Digital<h3/>

# Research Question
<li>Bagaimana metode Robert Filter dapat diterapkan secara efektif untuk ekstraksi fitur pada citra plat nomor kendaraan?<li/>
<li>Bagaimana kerangka kerja framing image dapat digunakan untuk memisahkan plat nomor kendaraan dari latar belakang dalam citra digital?<li/>
<li>Apakah kombinasi antara metode Robert Filter dan framing image mampu meningkatkan akurasi identifikasi plat nomor kendaraan dibandingkan dengan metode lainnya?<li/>
<li>Bagaimana pengolahan citra digital dapat memengaruhi kinerja sistem identifikasi plat nomor kendaraan?<li/>
<li>Apa tantangan utama yang dihadapi dalam mengembangkan sistem identifikasi plat nomor kendaraan menggunakan pendekatan ini, dan bagaimana tantangan tersebut dapat diatasi?<li/>

# Teori
Referensi : https://arxiv.org/abs/2012.09810 
<p>Metode NVIDIA untuk Video Super Resolusi menggunakan gambar frame beresolusi rendah yang terealisasi beserta vektor geraknya yang mengandung informasi tentang arah pergerakan setiap piksel dalam frame berikutnya dan memasukkannya ke dalam CNN yang disebut autoencoder konvolusional yang dilatih pada superkomputer untuk menghasilkan versi resolusi tinggi dari gambar frame secara berurutan.
Video yang dihasilkan menggunakan teknik Super Resolusi tidak akan pernah seakurat aslinya yang beresolusi tinggi karena teknik machine learning didasarkan pada pendekatan. Akurasi Super Resolusi diuji selama pelatihan neural network melalui penggunaan algoritma yang disebut 'fungsi kerugian' yang membandingkan gambar yang dihasilkan oleh neural network dengan gambar asli beresolusi tinggi yang disebut gambar ground-truth dengan mengukur berbagai atribut dari gambar tersebut dan menggunakan hasilnya untuk melatih neural network agar menghasilkan hasil yang lebih akurat. Untuk DLSS dari NVIDIA, "proses ini diulang puluhan ribu kali pada superkomputer hingga jaringan dapat menghasilkan gambar resolusi tinggi berkualitas tinggi secara andal".
<p/>
Referensi : https://digitalcommons.morris.umn.edu/horizons/vol10/iss2/4/ 
<p>DLSS 2.0 meningkatkan versi sebelumnya dengan memodifikasi pendekatan sebelumnya dan menambahkan yang lain seperti: 
1. Neural network dalam versi ini menggunakan data dari lebih banyak sumber dari versi sebelumnya. Ini termasuk tidak hanya frame saat ini dan vektor gerak, tetapi juga data temporal seperti frame sebelumnya, dan buffer kedalaman; serta data tentang eksposur dan kecerahan dari adegan permainan.
2. DLSS 2.0 menggunakan model yang sepenuhnya tergeneralisasi. Artinya, neural network dapat menghasilkan output berkualitas tinggi di berbagai permainan tanpa perlu dilatih secara khusus untuk setiap permainan. Dengan perubahan ini, teknologi ini dapat meluas secara lebih efektif ke lebih banyak permainan, sambil juga memudahkan pengembang game untuk merilis game mereka tanpa harus menunggu NVIDIA melatih model untuk setiap permainan.
3. Yang paling penting, DLSS 2.0 menggunakan Multi-Frame Super Resolusi. Di sini, jaringan saraf dilatih untuk menggunakan data temporal (data dari frame resolusi rendah sebelumnya) selain dari frame saat ini untuk meningkatkan resolusi rendah saat ini. Karena mengumpulkan sampel dari frame sebelumnya, jaringan saraf dapat lebih baik memulihkan detail yang hilang yang kurang dari gambar resolusi rendah tanpa mengada-ada detail yang tidak ada atau menciptakan artefak visual. Selain itu, DLSS 2.0 juga menggunakan pembelajaran mendalam untuk melakukan anti-aliasing dalam yang disebut Deep Learning Anti-Aliasing (DLAA). Anti-aliasing adalah teknik yang bertujuan untuk mengurangi tampilan bergerigi pada tepi melengkung dalam gambar.
<p/>
Referensi : https://lup.lub.lu.se/student-papers/record/9091182/file/9091183.pdf 
<p>Temporal anti-aliasing atau TAA adalah suatu teknik yang membagi beban komputasi selama beberapa frame, dengan menerapkan efek anti-aliasing secara bertahap dari waktu ke waktu. Teknik ini, yang menjelaskan mengapa disebut "temporal," yang melibatkan pengenalan variasi acak kecil yang dikenal sebagai "jittering," pada sampel disetiap frame. Dengan mengambil rata-rata kontribusi dari frame historis ini dari waktu ke waktu, dapat dicapai laju sampel efektif yang lebih tinggi per piksel. Meskipun ideal untuk mempertimbangkan kontribusi dari sebanyak mungkin frame untuk hasil optimal, menyimpan semua frame resolusi tinggi dalam memori seringkali tidak memungkinkan karena ukuran datanya yang besar. Namun, metode umum melibatkan pengambilan rata-rata kontribusi, yang membutuhkan penyimpanan hanya satu frame historis tambahan, dicapai melalui fungsi akumulasi iteratif.<p/>
