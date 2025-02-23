# praktikum-4-sistem-operasi

| Nama        | Tamam Rifky Aqila |
|--------------|------------|
| NIM        | 09030282327016 |
| Program Studi | Teknik Komputer |

## Proses Input Output I/O

</div>
<br>
<div class=item>
<p>1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file
baru.</p>
<img src="https://github.com/user-attachments/assets/9531762f-351c-4148-bf19-ea7bb9b27799" width ="300">
<p>Menampilkan isi direktori latihan5 secara lengkap dan menyimpannya ke daftar_latihan5.txt.</p>
<p>2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard output
ke file baru tanpa menghapus file baru sebelumnya.</p>
<img src="https://github.com/user-attachments/assets/26cf6d43-f974-4a03-8839-04d45ddf0e2a" width="300">
<p>Menyimpan informasi file /etc/passwd ke dalam daftar_passwd.txt tanpa menghapus data lama.</p>
<P>3. Urutkan file baru dengan cara membelokkan standard input.</P>
<img src="https://github.com/user-attachments/assets/69f46a4b-71e8-4601-9f0f-c3b604be5235" width="300">
<p>Mengurutkan isi daftar_latihan5.txt tanpa menyimpannya ke file baru.</p>
<p>4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file
baru.urut.</p>
<img src="https://github.com/user-attachments/assets/88651106-2075-45e0-b8aa-c4b61c5f0ebd" width="300">
<p>Mengurutkan isi daftar_latihan5.txt dan menyimpan hasilnya ke baru.urut.</p>
<p>5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file
rmdirerror.txt.</p>
<img src="https://github.com/user-attachments/assets/9436d728-58c0-4c83-9227-82c2a3dde323" width="300">
<p>Direktori latihan6 dibuat sekali. Jika Percobaan gagal karena latihan6 sudah ada, dan error maka disimpan ke rmdirerror.txt.</p>
<p>6. Urutkan kalimat berikut :
Jakarta
Bandung
Surabaya
Padang
Palembang
Lampung
Dengan menggunakan notasi here document (<@@@ …@@@)</p>
<img src="https://github.com/user-attachments/assets/a775677a-2da5-4330-b4c7-95ef63838b36" width="300">
<p>Memasukkan daftar kota secara manual dan mengurutkannya langsung tanpa menyimpan ke file.</p>
<p>7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan
tambahkan data tersebut ke file baru.</p>
<img src="https://github.com/user-attachments/assets/f08dd94f-24d2-4cc4-a071-29a622709721" width="300">
<p>Menghitung jumlah baris, kata, dan karakter dalam baru.urut. Menambahkan hasilnya ke hasil_wc.txt.</p>
<p>8. Gunakan perintah di bawah ini dan perhatikan hasilnya.
$ cat /etc/passwd | sort | pr –n | grep tty03
$ find /etc –print | head
$ head /etc/passwd | tail –5 | sort</p>
<img src="https://github.com/user-attachments/assets/ff1590b6-a18b-4bc9-be46-f129566cbde3" width ="300">
<p>Perintah ke 1 untuk Menampilkan isi /etc/passwd, mengurutkannya, lalu mencari entri dengan tty03. Perintah ke 2 untuk Menampilkan daftar file dalam /etc, tetapi hanya 10 baris pertama. dan Perintah ke 3 untuk Mengambil 10 baris pertama dari /etc/passwd, lalu menyaring 5 baris terakhir sebelum mengurutkannya.</p>
<p>9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.</p>
<img src="https://github.com/user-attachments/assets/4d2ec201-10c6-4005-adf0-d42e32a7b057" width="300">
<p>- who > Menampilkan daftar pengguna yang sedang login. tamam seat0 2025-02-23 19:11 (login screen) → Pengguna tamam login di seat0 pada 19:11. tamam tty2 2025-02-23 19:11 (tty2) → Pengguna tamam login di tty2 pada 19:11.

cat | cat >Tidak mengubah output, hanya meneruskan data yang sama.
sort > Mengurutkan daftar login berdasarkan abjad, tapi karena hanya ada satu user tamam, urutan tetap sama.
pr > Memformat output agar terlihat seperti dokumen dengan tambahan "Page 1" dan timestamp 2025-02-21 22:53.
head > Mengambil beberapa baris pertama dari output.
cat | tail > tail menampilkan bagian akhir dari hasil sebelumnya, sehingga tetap menampilkan seluruh output jika jumlah baris tidak terlalu banyak.</p>

## KESIMPULAN
Melalui latihan-latihan ini, pengguna dapat memahami dan mempraktikkan konsep dasar pengalihan input dan output di sistem operasi, yang esensial untuk pengelolaan file dan automasi tugas sehari-hari.
</div>
<br>







