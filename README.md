# Pertemuan-7-labspy02

Repositiry ini dibuat untuk memenuhi tugas Pertemuan 7 - Bahasa Pemrograman (Module Praktikum 2)<br><br>
Nama : Mohamad Farizal Arifin <br>
NIM : 312010231<br>
Kelas : TI.20.B.1<br>

Pada halaman ini (Tugas Pertemuan-7-Module Praktikum 2) Dosen memberi tugas yaitu untuk membuat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan
tersebut tampilkan bilangan terbesarnya. Gunakan statement if. Menggunakan Bahasa Pemrograman Python<br>

* Pada repository ini saya akan menjelaskan langkah atau algoritmanya serta Flowchart yang telah saya buat. file flowchart bisa klik link berikut <br>

Berikut source code yang saya tulis untuk membuat aplikasi tersebut.<br>
``` python
#membuat program module 2
print("Masukkan Pilihan Angka ke-1 : ")
xangka1 = int(input())
print("Masukkan Pilihan Angka ke-2 : ")
xangka2 = int(input())
print("Masukkan Pilihan Angka ke-3 : ")
xangka3 = int(input())

if (xangka1 > xangka2) and (xangka1 > xangka3):
    print(f"Bilangan Pertama ({xangka1}) lebih besar dari Bilangan kedua dan ketiga")
elif (xangka2 > xangka1) and (xangka2 > xangka3):
    print(f"Bilangan kedua ({xangka2}) lebih besar dari Bilangan pertama dan ketiga")
elif (xangka1 == xangka2) and (xangka1 == xangka3) and (xangka2 == xangka3):
    print("Bilangan yang dimasukkan sama besar")
else:
    print(f"Bilangan ketiga ({xangka3}) lebih besar dari Bilangan pertama dan kedua")

```
<br>
Hasil running dari source code diatas adalah seperti gambar dibawah<br>

![hasil running](pict/running.PNG)