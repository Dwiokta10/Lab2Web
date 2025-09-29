# Praktikum 2 : CSS Dasar

|                |                    |
| -------------- | ------------------ |
|      _Nama_    | Dwi Okta Ramadhani |
|      _NIM_     |      312410056     |
|     _Kelas_    |      TI.24.A1      |
|  _Mata Kuliah_ | Bahasa Pemrograman Web 1 |

**Hasil Output**

<img width="1920" height="1200" alt="web css" src="https://github.com/user-attachments/assets/9ff22525-0742-4f7c-8c7e-1f1473b22e4c" />



# Pertemuan 3 - Pemrograman Web

Proyek ini merupakan salah satu bentuk latihan dasar yang diberikan kepada mahasiswa dalam rangka mempelajari serta memahami penggunaan HTML dan CSS pada mata kuliah Pemrograman Web di Universitas Pelita Bangsa. Latihan ini tidak hanya sekadar mengajarkan cara menuliskan kode program, tetapi juga bertujuan memberikan pemahaman mendalam mengenai bagaimana sebuah halaman web dibangun mulai dari struktur paling sederhana hingga memiliki tampilan yang lebih menarik dan terorganisir.

Melalui proyek ini, mahasiswa diharapkan mampu menguasai konsep dasar pembuatan halaman web sederhana dengan memperhatikan struktur penulisan yang benar menggunakan elemen-elemen HTML, seperti heading, paragraf, link, gambar, tabel, maupun form. Selain itu, mahasiswa juga dituntut untuk mempelajari cara mengatur, memperindah, serta menyesuaikan tampilan halaman web dengan memanfaatkan berbagai metode penerapan CSS yang tersedia.

---

## Materi yang Dipelajari
1. **CSS Internal**  
   Menggunakan tag `<style>` di dalam file HTML.
   
2. **Inline CSS**  
   Menambahkan atribut `style` langsung pada elemen HTML, contoh:
   ```html
   <p style="text-align: center; color: #ccd8e4;">...</p>
3. **CSS Eksternal (Simulasi)**
Disimulasikan menggunakan block <style> kedua, meskipun seharusnya dipisah dalam file .css.

4. **Selector CSS**

ID Selector → #intro

Class Selector → .button, .btn-primary

Tag Selector → h1, nav, p

**Penjelasan Code**
```python
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
    
    <!-- CSS Internal -->
    <style>
        body {
            font-family: 'Open Sans', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        
        header {
            min-height: 80px;
            border-bottom: 1px solid #77CCEF;
            background-color: white;
        }
        
        h1 {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
            margin: 0;
        }
        
        h1 i {
            color: #6d6a6b;
        }
        
        #intro {
            background: #1271d6;
            border: 1px solid #fa0aa2;
            min-height: 100px;
            padding: 10px;
            margin: 20px;
            border-radius: 5px;
        }
        
        #intro h1 {
            text-align: left;
            border: 0;
            color: #fff;
            padding: 10px 0;
        }
        
        #intro p {
            color: white;
            line-height: 1.5;
        }
        
        .button {
            padding: 15px 20px;
            background: #bebcbd;
            color: #fff;
            display: inline-block;
            margin: 10px;
            text-decoration: none;
            border-radius: 4px;
        }
        
        .btn-primary {
            background: #E42A42;
        }
        
        .btn-primary:hover {
            background: #c21830;
        }
    </style>
    
    <!-- CSS Eksternal (disimulasikan dalam style tag) -->
    <style>
        /* Simulasi CSS Eksternal */
        nav {
            background: #d61073;
            color: #fff;
            padding: 10px;
        }
        
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        
        nav .active,
        nav a:hover {
            background: #08E8BA;
        }
    </style>
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
        <!-- Inline CSS pada paragraf -->
        <p style="text-align: center; color: #ccd8e4;">
            Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. 
            Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.
        </p>
        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>
</body>
</html>
```
### Terimakasih
