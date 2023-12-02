# Lab6Web
# Lab6Web, Framework
## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Ricky alfian saputra |
| **NIM** | 312210279 |
| **Kelas** | TI.22.A4 |
| **Mata Kuliah** | Pemrograman WEB |

### Intruksi
1. Buatlah repository baru dengan nama Lab6Web.
2. Kerjakan semua latihan yang diberikan sesuai urutannya.
3. Screenshot setiap perubahannya.
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta 
screenshotnya.
5. Commit hasilnya pada repository masing-masing.
6. Kirim URL repository pada e-learning ecampus.

### Tugas
- Buatlah layout web sederhana menggunakan css frameword (Twitter Bootsrtap).
- Berdasarkan gambar layout web berikut, buatlah menggunakan Twitter Bootstrap

### Jawaban : [Sourcecode](https://github.com/ricky1211/Lab6Web/blob/main/Layout6.html)
### Jawaban : [Sourcecode.CSS](https://github.com/ricky1211/Lab6Web/tree/main/css)

**Hasil tugas :**

![](https://github.com/ricky1211/Lab6Web/blob/main/LAB6/Screenshot%20(367).png?raw=true)
![](https://github.com/ricky1211/Lab6Web/blob/main/LAB6/Screenshot%20(368).png?raw=true)
![](https://github.com/ricky1211/Lab6Web/blob/main/LAB6/Screenshot%20(369).png?raw=true)

# Langkah-langkah Praktikum

## Sebelumnya, apa itu framework ?
**"Framework" dalam pengembangan perangkat lunak adalah seperangkat alat, konsep, aturan, 
dan komponen yang disusun secara terstruktur untuk membantu pengembang membangun aplikasi atau sistem perangkat lunak dengan lebih cepat dan efisien.**

```HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Framework</title>
    
    <!-- Style -->
    <link rel="stylesheet" href="style.css">

    <!-- Bootstrap -->
    <script src="js/bootstrap.js"></script>
    <script src="js/popper.min.js"></script>
    <link href="css/bootstrap.css" rel="stylesheet">    
</head>

<body class="text-body-secondary lh-1">
    <div class="container w-75 shadow-lg p-3 mb-0 bg-body-tertiary rounded" id="container">

        <header class="p-3">
            <h1 class="mt-2 mb-2 me-1 ms-1 text-body-tertiary fw-bold">Layout Sederhana</h1>
        </header>

        <nav class="bg-primary d-block">
            <a href="#"
                class="active pt-3 pb-3 ps-3 pe-3 text-white fs-6 fw-bold text-decoration-none d-inline-block">Home</a>
            <a href="#article"
                class="pt-3 pb-3 ps-3 pe-3 text-white fs-6 fw-bold text-decoration-none d-inline-block">Artikel</a>
            <a href="#about"
                class="pt-3 pb-3 ps-3 pe-3 text-white fs-6 fw-bold text-decoration-none d-inline-block">About</a>
            <a href="#contact"
                class="pt-3 pb-3 ps-3 pe-3 text-white fs-6 fw-bold text-decoration-none d-inline-block">Kontak</a>
        </nav>

        <section id="hero" class="bg-dark-subtle pb-5 pt-5 pe-3 ps-3 mb-2">
            <h1 class="mb-4 fs-1 fw-bold">Hello World!</h1>
            <p class="mb-3 fs-5 lh-base">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                pretium ac.</p>
            <a href="home.html" class="btn btn-large">Learn more &raquo;</a>
        </section>

        <section id="wrapper" class="m-0 position-relative">
            <section id="main" class="float-start w-75 p-2 ">
                <div class="row">
                    <div class="box pt-0 pb-0 pe-2 d-block float-none w-25">
                        <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle ms-4">
                        <h3 class="mt-2 mb-2 me-0 ms-0 text-center fs-4 fw-bold">Heading</h3>
                        <p class="lh-base fs-6 mb-2 text-center">Donec sed odio dui. Etiam porta sem malesuada magna
                            mollis
                            euismod.</p>
                        <a href="#" class="ms-5 fw-medium fs-6 btn bg-dark-subtle p-2 rounded">View detail</a>
                    </div>
                    <div class="box pt-0 pb-0 pe-2 ps-2 d-block float-start w-25 align-items-center">
                        <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="rounded-circle ms-4">
                        <h3 class="mt-2 mb-2 me-0 ms-0 text-center fs-4 fw-bold">Heading</h3>
                        <p class="lh-base fs-6 mb-2 text-center">Donec sed odio dui. Etiam porta sem malesuada magna
                            mollis
                            euismod.</p>
                        <a href="#" class="ms-5 fw-medium fs-6 btn bg-dark-subtle p-2 rounded">View detail</a>
                    </div>
                    <div class="box pt-0 pb-0 pe-2 ps-2 d-block float-start w-25 align-items-center">
                        <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="rounded-circle ms-4">
                        <h3 class="mt-2 mb-2 me-0 ms-0 text-center fs-4 fw-bold">Heading</h3>
                        <p class="lh-base fs-6 mb-2 text-center">Donec sed odio dui. Etiam porta sem malesuada magna
                            mollis
                            euismod.</p>
                        <a href="#" class="ms-5 fw-medium fs-6 btn bg-dark-subtle p-2 rounded">View detail</a>
                    </div>
                </div>

                <hr class="divider border-0 border-top border-light-subtle mb-3 mt-3 me-0 ms-0" />
                <article class="entry mb-2 mt-2 me-0 ms-0" id="article">
                    <h2 class="mb-2 fs-3 fw-bold">First featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="float-start rounded ms-2">
                    <p class="lh-base">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                        elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                        vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                        pretium ac.</p>
                </article>

                <hr class="divider  border-0 border-top border-light-subtle mb-3 mt-3 me-0 ms-0" />
                <article class="entry mb-2 mt-2 me-0 ms-0">
                    <h2 class="mb-3 fs-3 fw-bold">First featurette heading.</h2>
                    <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="float-end rounded ms-2">
                    <p class="lh-base">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
                        elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
                        vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
                        pretium ac.</p>
                </article>
            </section>

            <aside id="sidebar" class="float-start w-25 p-3">
                <div class="widget-box border border-secondary mb-3">
                    <h3 class="title pt-2 pb-2 ps-2 pe-2 bg-primary text-white fs-4">Widget Header</h3>
                    <ul class="list-unstyled">
                        <li class="border-bottom border-secondary"><a
                                class="pt-2 pb-2 pe-3 ps-3 text-success-emphasis d-block text-decoration-none"
                                href="#">Widget Link</a></li>
                        <li class="border-bottom border-secondary"><a
                                class="pt-2 pb-2 pe-3 ps-3 text-success-emphasis d-block text-decoration-none"
                                href="#">Widget Link</a></li>
                        <li class="border-bottom border-secondary"><a
                                class="pt-2 pb-2 pe-3 ps-3 text-success-emphasis d-block text-decoration-none"
                                href="#">Widget Link</a></li>
                        <li class="border-bottom border-secondary"><a
                                class="pt-2 pb-2 pe-3 ps-3 text-success-emphasis d-block text-decoration-none"
                                href="#">Widget Link</a></li>
                        <li class="border-bottom border-secondary"><a
                                class="pt-2 pb-2 pe-3 ps-3 text-success-emphasis d-block text-decoration-none"
                                href="#">Widget Link</a></li>
                    </ul>
                </div>

                <div class="widget-box border border-secondary mb-3">
                    <h3 class="title pt-2 pb-2 ps-2 pe-2 bg-primary text-white fs-4 border-">Widget Text</h3>
                    <p class="p-2 lh-base">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
                        arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
                        pharetra est nunc, nec pretium nunc pretium ac.</p>
                </div>
            </aside>
        </section>

    </div>
    <footer class="w-75 text-white bg-dark mx-auto p-2 text-center">
        <p>&copy; 2023 - Universitas Pelita Bangsa</p>
    </footer>
</body>

</html>
```
**Hasil :**

#### *Note :*
```CSS
    <!-- Style -->
    <link rel="stylesheet" href="style.css">
```
- Sebagai penghubung antara file `lab6_css_framework.html` dengan `style.css`

```HTML
    <!-- Bootstrap -->
    <script src="js/bootstrap.js"></script>
    <script src="js/popper.min.js"></script>
    <link href="css/bootstrap.css" rel="stylesheet">  
```
- Di sini saya mengdownload Bootstrap css & js dan menyimpan nya ke dalam file `web framework`
  jadi bisa di gunakan saat PC/Laptop dalam keadaan offline. 
