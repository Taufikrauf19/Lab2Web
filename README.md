# Lab2Web

## NAMA     : MOH. TAUFIK RAUF
## NIM      : 312010151
## KELAS    : TI.20.A1

# 1. MEMBUAT DOKUMEN HTML
<img width="959" alt="pertama" src="https://user-images.githubusercontent.com/101621391/159464314-b755d0e4-3b00-47cb-b698-25d3497ee017.png">

# Contoh coding
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

# 2. Mendeklarasikan CSS Internal
<img width="960" alt="kedua" src="https://user-images.githubusercontent.com/101621391/159464446-35023c75-6143-48ec-87ac-d4f243523fc7.png">
Ini adalah hasil Mendeklarasikan CSS Internal

# Contoh coding
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
