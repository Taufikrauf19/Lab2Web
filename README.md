# Lab2Web

## NAMA     : MOH. TAUFIK RAUF
## NIM      : 312010151
## KELAS    : TI.20.A1

#
# 1. MEMBUAT DOKUMEN HTML
<img width="959" alt="pertama" src="https://user-images.githubusercontent.com/101621391/159464314-b755d0e4-3b00-47cb-b698-25d3497ee017.png">

## Contoh coding
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>
<header>
<h1>CSS Internal dan <i>Inline CSS</i></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
<h1>Hello World</h1>
<p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
dan CSS.</p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>
```
#
# 2. Mendeklarasikan CSS Internal
<img width="960" alt="kedua" src="https://user-images.githubusercontent.com/101621391/159464446-35023c75-6143-48ec-87ac-d4f243523fc7.png">
Ini adalah hasil Mendeklarasikan CSS Internal

## Contoh coding
```
<head>
    <!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
    <title>CSS Dasar</title>
    <style>
    body {
    font-family:'Open Sans', sans-serif;
    }
    header {
    min-height: 80px;
    border-bottom:1px solid #000000;
    }
    h1 {
    font-size: 24px;
    color: #000000;
    text-align: center;
    padding: 20px 10px;
    }
    h1 i {
    color:#6d6a6b;
    }
    </style>
</head>
```
#
# 3. Menambahkan Inline CSS
<img width="960" alt="inline" src="https://user-images.githubusercontent.com/101621391/159464650-2cd09c13-ea29-49cf-a321-38596a1dd3c9.png">
Ini adalah hasi dari Menambahkan Inline CSS

## Contoh coding
```
<p> style="text-align: center; color: #ccd8e4;"> </p>
```
#
# 4. Membuat CSS Eksternal
<img width="131" alt="buat file" src="https://user-images.githubusercontent.com/101621391/159469421-583c6562-458d-4f41-a01d-087b565665d7.png">

Selanjutnya buatlah file baru dengan nama style_eksternal.css 
Caranya masukan Contoh codingan berikut :

## Contoh coding
```
nav {
    background: #555555;
    color:#fff;
    padding: 10px;
    }
nav a {
    color: #fff;
    text-decoration: none;
    padding:10px 20px;
    }
nav .active,
nav a:hover {
    background: #414141;
    }
```
Kemudian tambahkan tag ```<link>``` untuk merujuk file css yang sudah dibuat pada bagian ```<head>```.

Caranya yaitu, masukan contoh codingan berikut :
```
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
```
Setelah memasukan contoh codingannya, simpan dan pergi lagi ke browser kemudian refresh kembali browser tersebut dan lihatlah perubahannya.


<img width="960" alt="css" src="https://user-images.githubusercontent.com/101621391/159464745-2dacd66e-ad21-4623-a412-e4e80f5b2117.png">
Inilah contoh perubahannya

#
# 5. Menambahkan CSS Selector
Cara menambahkan CSS Selector adalah.

Gunakan ID dan Class Selector. Pada file
style_eksternal.css.

Cara menambahkannya ialah masukan kode berikut di file style_eksternal.css.
```
/* ID Selector */
#intro {
    background: #444444;
    border: 1px solid #000000;
    min-height: 100px;
    padding: 10px;
    }
    #intro h1 {
    text-align: left;
    border: 0;
    color: #fff;
    }
    /* Class Selector */
    .button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    }
    .btn-primary {
    background: #286936;
    }
```

Setelah menambahkan kodenya simpan (Ctrl s) filenya, dan pergi lagi ke broeser kemudian refresh, lihatlah perubahannya.
<img width="960" alt="cssselektor" src="https://user-images.githubusercontent.com/101621391/159464851-8e00e614-c232-450c-9a56-769e4fa62d6a.png">
Inilah contoh perubahannya