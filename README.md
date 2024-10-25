# Tugas Arsitektur dan Organisasi Komputer

Pengalamatan Langsung:

1. Hitung alamat yang diakses untuk instruksi LOAD A, 2000.<br>
Jawab :<br>
a. LOAD berarti mengambil data dari memori dan menempatkannya ke dalam register (pada soal ini, register A).<br>
b. alamat memori yang diberikan secara langsung adalah 2000.<br><br>
Jadi, alamat yang diakses adalah 2000<br><br>

Pengalamatan Tidak Langsung:

2. Jika register R1 berisi 1500, berapa alamat yang diakses untuk instruksi LOAD A, (R1)?<br>
Jawab :<br>
a. Nilai dalam register R1 adalah 1500.<br>
b. Pengalamatan tidak langsung berarti kita menggunakan nilai dalam register R1 sebagai alamat memori.<br><br>
Jadi, alamat yang diakses adalah 1500.<br><br>

Pengalamatan Indeks:

3. Hitung alamat yang diakses untuk instruksi LOAD A, 500 (R2) jika R2 = 100.<br>
Jawab :<br>
a. Nilai dalam register R2 adalah 100.<br>
b. Offset yang diberikan adalah 500 (offset digunakan bersama dengan nilai yang ada dalam register untuk menentukan alamat memori yang akan diakses).<br><br>
Alamat yang diakses = Nilai dalam R2 + Offset<br>
Alamat yang diakses = 100 + 500 = 600.<br><br>
Jadi, alamat yang diakses adalah 600.<br><br>

Pengalamatan Relatif:

4. Hitung alamat yang diakses untuk instruksi LOAD A, 40 jika alamat instruksi saat ini adalah 1200.<br>
Jawab :<br>
a. Alamat instruksi saat ini adalah 1200.<br>
b. Offset yang diberikan adalah 40.<br><br>
Alamat yang diakses = Alamat instruksi saat ini + Offset<br>
Alamat yang diakses = 1200 + 40 = 1240.<br><br>
Jadi, alamat yang diakses adalah 1240.<br><br>

Pengalamatan Segmen:

5. Berapa alamat yang diakses jika Segment Base = 4000 dan Offset = 300?<br>
Jawab :<br>
a. Segment Base = 4000.<br>
b. Offset = 300.<br><br>
Alamat Fisik = Segment Base + Offset<br>
Alamat Fisik = 4000 + 300 = 4300.<br><br>
Jadi, alamat yang diakses adalah 4300.<br><br>

Latihan Campuran:

6. Jika R3 = 250 dan instruksi adalah LOAD A, 1000 (R3), hitung alamat yang diakses.<br>
a. Nilai dalam register R3 adalah 250.<br>
b. Offset yang diberikan adalah 1000.<br><br>
Alamat yang diakses = Nilai dalam R3 + Offset<br>
Alamat yang diakses = 250 + 1000 = 1250.<br><br>
Jadi, alamat yang diakses adalah 1250.<br><br>
