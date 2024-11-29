# books

~ menambahkan getData dan mengedit pubspec.yaml
![image](https://github.com/user-attachments/assets/0d97dada-5bb5-4099-9b7b-d63ff7a44af8)
![image](https://github.com/user-attachments/assets/889880b4-2a5c-447b-8b25-3a648e62dca3)

W11: Soal 3
result = value.body.toString().substring(0, 450);
value.body sebagai respon API yang dikonversi menjadi string
substring digunakan untuk membatasi karakter pertama sebanyak 450 yang disimpan pada variable result. 
![image](https://github.com/user-attachments/assets/23a471ef-2dac-445c-b14f-30f4e1e18a5b)

W11: Soal 4
kode 1
pada returnOneAsync digunakan untuk menunggu await selama 1 detik
pada returnTwoAsync digunakan untuk menunggu await selama 2 detik
pada returnThreeAsync digunakan untuk menunggu await selama 3 detik
kode 2
child digunakan sebagai properti isi tombol
onpressed(){} digunakan sebagai aksi apa yang dilakukan ketika tombol ditekan
count() digunakan memanggil fungsi count
![image](https://github.com/user-attachments/assets/e5c1e2e8-8a3e-47d0-ace4-1a5aa02a401f)

W11: Soal 5
late Completer completer;
Completer digunakan untuk memberikan kontrol secara manual terhadap penyelesaian sebuah fitur
get Number(){
menginisialisasi Completer<int> dan memanggil fungsii calculate()
mengembalikan Future yang akan selesai ketika Completer diselesaikan dengan completer.complete()
calculate()
fungsi await digunakan untuk menunggu selama 5 detik menggunakan future delayed, lalu mnyelesaikan completer.complete(42)
![image](https://github.com/user-attachments/assets/ad0234bc-9a45-41b8-bbd9-2b6cf1ac2778)

W11: Soal 6
perbedaan dalam kedua potong kode tersebut adalah ketika penangkapan error. dalam kode pertama tidak ada penangkapan jika terdapat error, tetapi pada kode kedua menggunakan try-catch dalam menangkap sebuah error
![image](https://github.com/user-attachments/assets/9b9ec090-00ef-492e-b4e2-17e7a1f9fddf)

W11: Soal 7
![image](https://github.com/user-attachments/assets/561af297-ec6b-429e-bd6c-002a5ce2d151)

W11: Soal 8
perbedaanya adalah pada FutureGroup bis amenambahkan Future secara dinamis, sedangkan Future.wait harus tau dari awal.
kode dalam FutureGroup lebih kompleks, sedangkat Future.wait lebih sederhana.
FutureGroup menambahkan Future secara bertahap atau dinamis, sedangkan Future.wait sudah diketahui dari awal.

W11: Soal 9
![image](https://github.com/user-attachments/assets/01c55b4b-7293-4a60-af11-e509b12324c5)

W11: Soal 10
tidak ada futurepagestate

W11: soal 13 dan 14
tidak ada perbedaan UI apapun dikarenakan hal ini hanya memanajemen kode tanpa mengubah UI
![image](https://github.com/user-attachments/assets/e652894b-62c7-4bc9-af45-455cbdfb4479)

w11: soal 16
ketika di klik maka akan ganti warna sesuai dengan warna yang kita pilih. dikarenakan pada navigation first merupakan awal saat masuk ke dalam halaman, ketika di klik change color maka akan berpindah ke nvigation second. navigation tersebut terdaapat pada navigation first. lalu pada navigation second disediakan 3 warna, yang sudah dideklarasikan pada class _navigationSecondState yaitu Color color; itu akan mengubah backround warna ketika di klik warna yang diingikan.
![image](https://github.com/user-attachments/assets/776015ff-9d3b-472d-95c4-4796cce44a86)


w11: soal 17
- setiap di klik button akan berganti backround warna, dikarenakan dalam scaffold dideklarasikan backround: kan color; dan pada dalam onpressed dilogikakan. maka setiap di klik akan ganti warna.
- ![image](https://github.com/user-attachments/assets/2869eed6-90ad-4903-931e-6c01f01fdfdc)




A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
