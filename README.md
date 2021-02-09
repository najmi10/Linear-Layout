# Linear Layout
Linear Layout adalah susunan tata letak yang paling simple dapat digunakan para
developer android. Karena layout ini hanya memberikan susunan tata letak komponen secara
garis lurus. Bisa secara horizontal maupun vertical.Jadi di dalam setiap baris/kolom hanya ada 1 objek (widget) yang kita tempatkan. 
Nahh di Linear Layout ini ada dua jenis, yaitu:
- [x] Vertical Linear Layout : Apabila user menempatkan 1 widget (objek) per baris
- [x] Horizontal Linear Layout : Apabila user menempatkan 1 objek per kolom

![AltText](https://github.com/najmi10/Linear-Layout/blob/master/LinearLayout.png)
# Jawaban Soal
1. Perbedaan Linear Layout, Relative Layout, dan Constraint Layout
1. Linear Layout adalah jenis layout dimana user menempatkan 1 objek per baris atau kolom secara sejajar. Jadi di dalam setiap baris atau kolom hanya ada 1 objek yang bisa ditempatkan . Linear Layout ini ada dua jenis . Yaitu : Linear Layout Vertical (Objek per baris/kesamping) dan Linear Layout Horizontal (Objek per kolom/kebawah)
2.  Relative Layout adalah jenis layout yang memiliki karakteristik dalam menempatkan view secara relatif. Relatif disini berarti posisi dari setiap view bergantung kepada view yang lain. Mudahnya adalah, kita bebas untuk menempatkan objek yang diinginkan sesuka hati kita. Penempatan satu objek bisa dimana saja mau di sisi kanan, kiri, atas, ataupun bawah dari objek lain. Jika tidak di tetapkan, maka objek dapat menumpuk antara satu objek dengan objek yang lain.
3. Constraint Layout memungkinkan kita membuat tata letak yang besar dan kompleks dengan tampilan datar. Ini hampir mirip dengan Relative Layout karena semua tampilan ditata berdasarkan hubungan antara satu objek dengan yang lain, tetapi lebih fleksibel daripada Relative Layout dan lebih mudah digunakan dengan Editor Layout Android Studio.
- [x] Jadi Linear Layout bisa mengikuti ukuran layar handphone yang berbeda-beda tanpa merubah susuan objek, Relative Layout hanya akan terlihat sesuai dengan apa yang telah ditetapkan sebelumnya jika ukuran layar berubah bisa saja objek ada yang terpotong atau bahkan tidak terlihat, sedangkan Contraint Layout itu lebih flexible dan mudah untuk dibuat.
2. Penjelasan Method onCreate dan onPause
- [x] onCreate Untuk menginisiasi suatu activity, biasanya dipanggil dengan perintah
setContentCiew(int) untuk resource yang didefinisikan di layout UI, dengan perintah
findViewById(int) untuk memanggil widget yang dibutuhkan UI untuk berinteraksi dengan
aplikasi.
- [x] onPause Untuk menyatakan ketika user meninggalkan suatu activity. Untuk penggunaan
dengan Context.StartActivity(), semua kelas activity harus sesuai dengan yang dideklarasikan
dalam suatu paket di AndroidManifest.xml. Activity adalah bagian penting dari model aplikasi.
