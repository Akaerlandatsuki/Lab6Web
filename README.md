# Lab6web
tugas pertemuan 7-pemrograman web

Repository ini dibuat untuk memenuhi tugas mata kuliah pemrograman web.

Nama    : Aka erlanda

Nim     : 312010207

Kelas   : TI.20.B.1

<b>soal</b>

Buatlah Sebuah Layout sederhana seperti pada tugas praktikum 4. Tetapi dengan menggunakan css framework (twitter bootstrap).

<b>Membuat Header , Hero , dan Navigation menu</b>

Disini saya tidak mengunduh file bootsrap nya melainkan saya membuat layout dengan menggunakan bootstrap cdn dimana penggunaan nya harus menggunakan koneksi internet atau online. Dan ssaya juga disini masih menggunakan css eksternal untuk modified nya.

Berikut Source code pembuatan header, nav, dan section hero di file index.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tugas Pertemuan 7</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div class="container" style="box-shadow: 0 0 1em #cccccc">
      <div class="row">
        <header>
          <h1>Layout Sederhana</h1>
        </header>
      </div>
      <div class="row">
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
          <div class="container-fluid">
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Article</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Kontak</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
      <div class="row">
        <section id="hero">
          <h1>Hello World</h1>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Omnis laboriosam aspernatur ipsa magnam nulla voluptatem reiciendis! Exercitationem doloribus, quos nesciunt aut nobis cum consequatur expedita ad ex veniam assumenda
            provident?
          </p>
          <a class="btn btn-primary btn-sm" href="#" role="button">Learn More</a>
        </section>
      </div>
    </div>
  </body>
</html>





