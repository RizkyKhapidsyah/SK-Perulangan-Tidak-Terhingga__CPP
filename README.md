# SK-Perulangan-Tidak-Terhingga__CPP
Bahan Ajar Fundamental Pemrograman C++ - Studi Kasus; Perulangan Tidak Terhingga<br><br>

---

Perulangan tak berhingga merupakan perulangan (loop) yang tak pernah berhenti atau mengulang terus,<br>
hal ini sering terjadi disebabkan adanya kesalahan penanganan kondisi yang dipakai untuk keluar dari loop.<br><br>

<img src="https://github.com/RizkyKhapidsyah/SK-Perulangan-Tidak-Terhingga__CPP/blob/master/SK-Perulangan-Tidak-Terhingga__CPP/Result/001.PNG"><br><br>
Lihat Source Code : <br>
- <a href="https://github.com/RizkyKhapidsyah/SK-Perulangan-Tidak-Terhingga__CPP/blob/master/SK-Perulangan-Tidak-Terhingga__CPP/Source.cpp">Program</a><br><br>

---

Pada pernyataan ini tidak akan berhenti untuk menampilkan bilangan menurun,<br>
kesalahan terjadi pada pengubah nilai pencacah, seharusnya penulisan yang benar berupa<br><br>
<code>bil--</code>
<br><br>
Akan tetapi yang ditulis adalah :<br><br>
<code>bil++</code>
<br><br>
Oleh karena kondisi <code>bil >= 1</code> selalu bernilai benar (karena <code>bil</code> bernilai 6), <br>
maka pernyataan : <br><br>
<code>printf("%d", bil);</code>
<br><br> 
akan terus dijalankan. Jika terjadi hal semacam ini, untuk menghentikan proses yang terus menerus <br>
semacam ini denan menekan tombol <b>CTRL – PAUSE atau CTRL – BREAK.</b>
