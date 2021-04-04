# Praktikum 2 - Pemrograman Web (CSS Dasar)

### Rofi Ismail - 311910657
### TI.19.A.2

## Langkah 1
Membuat sebuah dokumen html sebagai berikut:
![SS - 1](https://user-images.githubusercontent.com/56240078/113502784-9f777980-9558-11eb-830d-59068d03fd38.jpg)

## Langkah 2
Mendeklarasikan CSS internal dalam bagian `<head>` dokumen.
![SS - 2_LI](https://user-images.githubusercontent.com/56240078/113502952-5116aa80-9559-11eb-832b-0fd85d1ff65d.jpg)

## Langkah 3
Mendeklarasikan inline CSS pada paragraf atau tag `<p>`.
![SS - 3_LI](https://user-images.githubusercontent.com/56240078/113503059-af438d80-9559-11eb-9536-6ea7a71ad1ef.jpg)

## Langkah 4
Membuat CSS eksternal dan menambahkan tag `<link>` pada bagian `<head>` dalam dokumen html untuk memuat dokumen css eksternal tersebut.
![SS - 4_LI](https://user-images.githubusercontent.com/56240078/113503209-8b347c00-955a-11eb-8229-995105713479.jpg)

Berikut hasilnya setelah browser direfresh.
![SS - 4-2](https://user-images.githubusercontent.com/56240078/113502788-a2726a00-9558-11eb-8aae-ce2726cb1380.jpg)

## Langkah 5
Menambah CSS Selector dengan menggunakan ID dan Class Selector pada dokumen css eksternal.
![SS - 5_LI](https://user-images.githubusercontent.com/56240078/113503272-f8481180-955a-11eb-8ef2-f6c7d8ed13a4.jpg)

# Pertanyaan dan Tugas
### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
* Saya melakukan beberapa eksperimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti background.
![SS - 6](https://user-images.githubusercontent.com/56240078/113504203-d5206080-9560-11eb-93cc-3485d0a4e6c7.jpg)

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
* Pendeklarasian CSS elemen h1 mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.

### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Setelah saya mencoba, jika mendeklarasikan CSS pada elemen yang sama namun dengan isi deklarasi yang berbeda, maka semua deklarasi CSS tersebut akan ditampilkan. Contohnya:
![SS - 7](https://user-images.githubusercontent.com/56240078/113504943-e324b000-9565-11eb-853e-c5578fc5f1b7.jpg)
![SS - 7-2](https://user-images.githubusercontent.com/56240078/113504944-e4ee7380-9565-11eb-92d3-9a5ce6fb66d7.jpg)

* Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya akan menampilkan salah satunya, dengan urutan Inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.
![SS - 7-2-1](https://user-images.githubusercontent.com/56240078/113505083-dd7b9a00-9566-11eb-892f-9f35463bd385.jpg)
![SS - 7-2-2](https://user-images.githubusercontent.com/56240078/113505085-df455d80-9566-11eb-8ed8-f40c6add1759.jpg)

### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Kedua deklarasi tersebut akan tampil, namun selector ID yang akan tampil jika deklarasinya ada yang sama antara ID dan Class.
![SS - 8](https://user-images.githubusercontent.com/56240078/113505654-74962100-956a-11eb-92da-7ce404c59c26.jpg)
![SS - 8-2](https://user-images.githubusercontent.com/56240078/113505656-765fe480-956a-11eb-9333-170d3fa16723.jpg)
