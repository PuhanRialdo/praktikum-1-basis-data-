**PRAKTIKUM 1**

1. jalankan Apache dan MySQL pada XAMPP
   <img width="502" alt="Screenshot 2024-02-16 153559" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/e3cb5ab4-f664-40c0-931e-68bae6cf9d6f">
   
2. ke pencarian lalu buka http://localhost/phpmyadmin dan membuat database baru
   <img width="960" alt="Screenshot 2024-02-16 174902" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/0154e9bc-16c3-47f5-bd11-1ef411418fcc">

3. merestore database penjualan_produk melalui menu inport
   <img width="960" alt="Screenshot 2024-02-16 174902" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/07321a42-98b0-4e06-b3ae-b487065c13dc">

4. Tabel akan muncul
   <img width="183" alt="Screenshot 2024-02-15 211133" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/7758cd92-756c-4c7f-a817-fdc5d5835598">

**PRAKTIKUM 2**

1. Design Menu
   ![WhatsApp Image 2024-02-16 at 18 14 56_cf6b630c](https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/24d619be-55d4-4c4f-b29e-fb0be574d7f7)

**PRAKTIKUM 3**

Soal
1. kode_penjualan = 3 tgl = 8 Februari 2021 kasir = Dini total_penjualan = 10.000
  <img width="960" alt="Screenshot 2024-02-16 184905" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/403f9ae0-8360-4c77-906b-6e4083d2ae4b">
  Caranya pergi ke menu penjualan lalu insert masukkan data yang ingin ditambahkan

2. kode_penjualan = 2 tgl = 10 Februari 2021 kasir = Dini total_penjualan = 20.000
   <img width="960" alt="Screenshot 2024-02-16 184905" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/72c436ab-c7cc-4ab9-90d6-16c54669f007">
   caranya hanya dengan mengulangi proses yang sama sseperti diatas

3. Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan!
   <img width="960" alt="Screenshot 2024-02-16 184905" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/f1176516-d659-4640-a2ce-eca96219044e">
   caranya adalah kode penjualan tidak boleh sama 

4. kode_penjualan = 2 kode_barang = 3 harga = 5.000 jumlah = 5
   <img width="960" alt="Screenshot 2024-02-16 184905" src="https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/c1f367e8-3b29-4554-916e-9e2df571d316">
   Data bisa ditambahkan karena data sudah tervalidasi ke (kode_penjualan dan kode_barang). Sudah masuk ke dalam tabel, maka data detail_penjualan dan kode_penjualan bisa 
   ditambahkan.

5. Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan
Jawaban. bisa emiliki akses ke dalam data, serta mengetahui tipe data dan nama kolom dan cara menambahkannya.

6. Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data
Jawaban.kode penjualan "2" disini dipakai sebanyak 2 kali dan akan membuat data error karena sudah terpakai lebih dari 2 kali

**PRAKTIKUM 4**

7. kode_penjualan = 2 kode_barang = 3 harga = 5.000 jumlah = 5 apakah bisa ditambahkan? jelaskan alasannya?
   ![Screenshot (74)](https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/8bbd87ae-a8ce-4e69-8498-f0083c78acd7)
jawab: Tidak bisa ditambahkan karena data sudah ada sebelumnya

8. Tidak bisa ditambahkan lagi, karena relasi antar tabel sudah dihapus, maka kode_pembelian dan detail_penjualan tidak memiliki hubungan
  ![WhatsApp Image 2024-02-16 at 19 27 25_b7ec4966](https://github.com/PuhanRialdo/praktikum-1-basis-data-/assets/160216825/37a97a4d-21f2-46ef-be5c-999bfe689bda)

9. Ulangi kembali langkah ke-1 pada praktikum 4. Apakah data dapat ditambahkan? jelaskan alasannya
jawaban. meskipun hubungan dari  kedua data dihapus, tetap saja data penjualan ke 2 sudah ada, tetap tidak bisa di tambahkan dengan kode penjualan 2.   
   
