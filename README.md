# Praktikum Pemrograman Web - CSS Dasar

Repository ini berisi file hasil praktikum CSS dasar menggunakan HTML dan CSS.  
Setiap langkah praktikum dijelaskan di bawah ini beserta hasil screenshot.

---

## 1. Membuat File HTML Dasar
Pertama membuat file `lab2_css_dasar.html` dengan struktur HTML sederhana:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Dasar</title>
</head>
<body>
    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
</body>
</html>

![hasil Output 1](https://raw.githubusercontent.com/rafiubaydillah53-design/Lab2web/5b679b0b247fa603725d94a7a17df86030f895db/hasil%20output%201.png)

2. Menambahkan Navigasi dengan CSS Eksternal
Selanjutnya membuat file `style_eksternal.css` dan menambahkan kode berikut:

```css
nav {
    background: #20A759;
    color: #fff;
    padding: 10px;
}
nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
}
nav .active,
nav a:hover {
    background: #0B6B3A;
}

![hasil Output 2](https://raw.githubusercontent.com/rafiubaydillah53-design/Lab2web/5b679b0b247fa603725d94a7a17df86030f895db/hasil%20output%201.png)

3.Menggunakan ID Selector

Menambahkan selector ID pada elemen #intro dengan kode CSS berikut:

#intro {
    background: #418fb1;
    border: 1px solid #099249;
    min-height: 100px;
    padding: 10px;
}
#intro h1 {
    text-align: left;
    border: 0;
    color: #fff;
}

![hasil Output 3](https://raw.githubusercontent.com/rafiubaydillah53-design/Lab2web/5b679b0b247fa603725d94a7a17df86030f895db/hasil%20output%201.png)

4.Menggunakan Class Selector

Menambahkan selector Class dengan kode CSS berikut:

.button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
}
.btn-primary {
    background: #E42A42;
}


Hasil Output:

5.Menggabungkan ID dan Class Selector

Menggunakan kombinasi ID dan Class dalam halaman HTML agar tampilan lebih menarik.
Contoh penggunaannya dalam HTML:

<section id="intro">
    <h1>Belajar CSS Dasar</h1>
    <a href="#" class="button">Button Biasa</a>
    <a href="#" class="button btn-primary">Button Merah</a>
</section>





