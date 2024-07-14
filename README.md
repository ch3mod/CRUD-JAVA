Konstruktor penjualan():

Deskripsi: Inisialisasi komponen GUI, mengatur koneksi ke database, dan mengkonfigurasi model tabel untuk jTable1.
Metode simpanData():

Deskripsi: Menyimpan data dari form ke tabel penjualan di database dan menambahkan data tersebut ke dalam tabel jTable1.
Metode initComponents():

Deskripsi: Menginisialisasi komponen GUI, seperti panel, label, tombol, tabel, dan field input.
Metode jButton1ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Mengatur semua field input pada form menjadi kosong untuk memulai entri data baru.
Metode jButton2ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Mengambil data dari form, menghitung jumlah bayar, diskon, dan total bayar, serta menampilkan data tersebut di tabel jTable1.
Metode jButton3ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Memanggil metode simpanData() untuk menyimpan data ke database.
Metode jButton4ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Menutup aplikasi.
Metode jTextField1ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Placeholder untuk menangani aksi pada jTextField1 (saat ini kosong).
Metode jComboBox1ActionPerformed(java.awt.event.ActionEvent evt):

Deskripsi: Mengatur jTextField1 dan jTextField2 berdasarkan item yang dipilih di jComboBox1.
Metode main(String args[]):

Deskripsi: Menjalankan aplikasi dan membuat instance dari kelas penjualan.
