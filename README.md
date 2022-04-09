# Lab4Web

**Nama	   	: Siti Latifah** <br>
**Nim	  	  : 312010321** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Pemrograman Web** <br>

# Soal

![image](https://user-images.githubusercontent.com/73010098/161433443-8071121d-aadb-46e4-993b-d8c0028f7409.png)

## Membuat Box Element
Persiapan membuat dokumen HTML menambahkan deklarasi CSS pada head untuk membuat float element, dengan nama file lab4_box.html seperti berikut

![image](https://user-images.githubusercontent.com/73010098/161433471-78eb09e5-98ee-497f-9ade-62150dda380d.png)

<b> Mengatur Clearfix Element </b> <br>
Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya.
Menambahkan element div lainnya setelah div3
``` html
<div class=”div4”>Div 4</div>
```
Kemudian atr property clear pada CSS
``` html
.div4 {
	Background-color: blue;
	Clear: left;
	Float: none;
}
```
![image](https://user-images.githubusercontent.com/73010098/161433570-d220f165-179e-43f0-aa04-05b52e596003.png)

# Membuat layout sederhana <br>
Kemudian ketik kode berikut

![image](https://user-images.githubusercontent.com/73010098/161433679-a42a4f00-1463-4af9-bd36-4640619d1f15.png)

Kemudian tambahkan kode CSS untuk membuat Layoutnya

![image](https://user-images.githubusercontent.com/73010098/161433700-311d82ea-04bf-449e-bb02-8ba9b77c9dcd.png)

<b> Membuat Navigasi </b> <br>

![image](https://user-images.githubusercontent.com/73010098/161433724-ff34336e-bc87-441b-9c70-b5d0970b737a.png)

<b> Membuat Hero Panel </b> <br>
Selanjutnya membuat hero panel. Tambahkan kode HTML dan CSS seperti berikut

![image](https://user-images.githubusercontent.com/73010098/161433747-391793aa-a3af-42be-9f14-fa2054a21169.png)

## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/161433767-cfc7789d-32fc-4b19-b4f4-3b88b48c1ea5.png)

<b> Mengatur Layout Main dan Sidebar </b> <br>
Selanjutnya mengatur main content dan sidebar, tambahkan CSS Float

![image](https://user-images.githubusercontent.com/73010098/161433798-43c4fd0b-ecad-41a3-a3fe-e1031a493e5d.png)

<b> Membuat Sidebar Widget </b> <br>
Kemudian selanjutnya menambahkan element lain dalam sidebar dan tambahkan CSS

![image](https://user-images.githubusercontent.com/73010098/161433818-9109ed99-997d-4422-be58-987a131671b5.png)

## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/161433831-c00f4669-d413-464b-85cf-589e0e4aa05f.png)

<b> Mengatur Footer </b> <br>
Selanjutnya mengatur footer, dan tambahkan CSS untuk footer

![image](https://user-images.githubusercontent.com/73010098/161433849-dc3690e6-fa6f-43b7-a75e-88978df80562.png)

<b> Menambahkan element lainnya pada Main Content </b>

![image](https://user-images.githubusercontent.com/73010098/161433897-ca6eae4a-d8ed-4c74-b8a4-eb140fb9355d.png)

Kemudian Tambahkankan CSS

![image](https://user-images.githubusercontent.com/73010098/161433916-c06f61b2-ff48-46c0-98fb-1a193ff39dfc.png)

## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/161433926-a38e67be-6a46-4a53-8710-be522019d1ae.png)

<b> Menambahkan Content Artikel </b> <br>
Selanjutnya membuat content artikel. Tambahkan HTML dan CSS berikut pada main content.

![image](https://user-images.githubusercontent.com/73010098/161433949-516d5611-f4a4-4d69-ad54-febdc5beef7b.png)

## OUTPUT

![image](https://user-images.githubusercontent.com/73010098/161433971-579e1f0a-e0c2-4759-b284-416bd3c56d92.png)

![image](https://user-images.githubusercontent.com/73010098/161433987-a8095563-79fe-4a15-96e9-91c269946e93.png)

## JAWABAN
# 1. LAYOUT MENU ABOUT
**Berikut Syntax HTML**
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana HTML</title>


<link rel="stylesheet" href="style.css">


</head>
<body>


    <div id="container">    


    <header>
        <h1>Layout Sederhana</h1>
    </header>
 <nav>
    <a href="home.html" class="active">Home</a>
    <a href="artikel.html">Artikel</a>
    <a href="about.html" class="active">About</a>
    <a href="kontak.html">kontak</a>
</nav>

    <section id="hero"></section>
    <section id="wrapper"></section>
    <section id="main"></section>
    <aside id="sidebar"></aside>


<!-- MENAMBAHKAN WRAPPER -->
<section id="wrapper">
	<h1><center>PROFILE</center></h1>
    <center>
	<img src="foto.jpg" alt="" width="200">
    </center>
    <p></p>
	<p>Perkenalkan nama saya Siti Latifah Saya bertempat tinggal di Cikarang Utara, Tempat Tanggal lahir 25 Juli 2002,
	   saya lulusan dari SMK Annihayah Jurusan Multimedia tahun lulus 2020, Sekarang Saya berkuliah di Universitas Pelita Bangsa 
	   Prodi Teknik jurusan Teknik Informatika.</p>

    <p><b>SKILL</b></p>
    <li>Editing Video</li>
    <li>Desain Grafis</li>
    <li>Editing Photo</li>
    
	<a href="about.html" class="active">About</a>
</section>
	
	<footer>
    <p>&copy; 2021 - Universitas Pelita Bangsa</p>
    </footer>

</div>
</body>
</html>
```
**Berikut Syntax CSS** <br>

``` css
/* Reset CSS */

* {
margin: 0;
padding: 0; 
}
    
    body {
        line-height:1; 
        font-size:100%; 
        font-family:'Open Sans', sans-serif;
        color:#5a5a5a; 
    }
    #container { 
        width: 980px;
        margin: 0 auto; 
        box-shadow: 0 0 1em #cccccc; 
    }

/* header */

    header { 
        padding: 20px; 
    }
    header h1 { 
        margin: 20px 10px; 
        color: #b5b5b5; 
    }

/* navigasi */
    nav {
        display: block;
        background-color: #1f5faa;
    }
    nav a {
        padding: 15px 30px;
        display: inline-block;
        color: #ffffff;
        font-size: 14px;
        text-decoration: none;
        font-weight: bold;
    }
    nav a.active,
    nav a:hover {
        background-color: #2b83ea;
    }
    
 /* Wrapper */
    #wrapper {
        background-color: #e4e4e5;
        padding: 20px 20px;
        margin-bottom: 0px;
    }
    #wrapper h1 {
        margin-top: 0%;
        margin-bottom: 10px;
        font-size: 35px;
    }
    #wrapper p {
        margin-bottom: 20px; 
        font-size: 18px;
        line-height: 25px; 
    }
   /* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
   }
```

## OUTPUT
![Screenshot (216)](https://user-images.githubusercontent.com/73010098/162575362-7e288994-474e-48a9-80f2-e71d9de37b75.png)
![Screenshot (217)](https://user-images.githubusercontent.com/73010098/162575365-1d61834f-d6a5-4100-b6b4-6418db383bad.png)

## 2.LAYOUT MENU KONTAK
**Berikut Syntax HTML**
``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Sederhana HTML</title>

    <link rel="stylesheet" href="style.css">

</head>
<body>

    <div id="container">    


        <header>
            <h1>Layout Sederhana</h1>
        </header>
     <nav>
        <a href="home.html" class="active">Home</a>
        <a href="artikel.html">Artikel</a>
        <a href="about.html" class="active">About</a>
        <a href="kontak.html" class="active">kontak</a>
    </nav>
    
        <section id="hero"></section>
        <section id="wrapper"></section>
        <section id="main"></section>
        <aside id="sidebar"></aside>
 
 <!-- Menambahkan Main -->
 <section id="hero">
    <h1>CONTACT</h1>
        <form action="proses.php" method="POST">
            <fieldset>
                <legend>Contact</legend>
                <div class="form">
                    <label for="nama">Nama</label>
                    <input type="text" id="nama" placeholder="Masukan Nama">
                </div>
                <div class="form">
                    <label for="email">E-Mail</label>
                    <input type="email" id="email" placeholder="Masukan E-Mail">
                </div>
                <div class="form">
                    <label for="pesan">Pesan</label>
                    <textarea rows="13" placeholder="Masukan Pesan"></textarea>
                </div>
                    <button type="submit" class="btn btn-danger">Kirim</button>
            </fieldset>
        </form>
 </section>

</body>
</html>
```

**Berikut Syntax CSS**
``` css
/* Reset CSS */

* {
margin: 0;
padding: 0; 
}
    
    body {
        line-height:1; 
        font-size:100%; 
        font-family:'Open Sans', sans-serif;
        color:#5a5a5a; 
    }
    #container { 
        width: 980px;
        margin: 0 auto; 
        box-shadow: 0 0 1em #cccccc; 
    }

/* header */

    header { 
        padding: 20px; 
    }
    header h1 { 
        margin: 20px 10px; 
        color: #b5b5b5; 
    }

/* navigasi */
    nav {
        display: block;
        background-color: #1f5faa;
    }
    nav a {
        padding: 15px 30px;
        display: inline-block;
        color: #ffffff;
        font-size: 14px;
        text-decoration: none;
        font-weight: bold;
    }
    nav a.active,
    nav a:hover {
        background-color: #2b83ea;
    }

/* Hero Panel */
    #hero {
        background-color: #e4e4e5;
        padding: 20px 20px;
        margin-bottom: 0px;
    }
    #hero h1 {
        margin-bottom: 20px;
        font-size: 35px;
    }
    #hero p {
        margin-bottom: 20px; 
        font-size: 18px;
        line-height: 25px;
    }
    #legend {
        text-align: center;
        font-family: sans-serif;
    }

/* Input */
input {
    width: 99%;
    font-family: 'Open Sans';
}
.form {
    margin-top: 25px;
    margin-left: 15px;
    font-family: 'Open Sans';
}
label {
    margin-left: 12px;
    font-family: 'Open Sans';
}
input {
    width: 97%;
    padding: 10px 15px;
    margin: 10px 10px;
    box-sizing: border-box;
    font-family: 'Open Sans';
}
textarea {
    width: 97%;
    padding: 10px 15px;
    margin: 10px 10px;
    box-sizing: border-box;
    font-family: 'Open Sans'; 
}
button[type=submit] {
    margin-left: 25px;
    padding: 10px 10px;
    margin-bottom: 25px;
    margin-top: 15px;
    background-color: #0a009b;
    border: 1px solid #0057f8;
    color: #fff;  
    font-weight: bold;
    font-family: 'Open Sans';
}
/* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
 }
 ```
 ## OUTPUT
 ![Screenshot (214)](https://user-images.githubusercontent.com/73010098/162575691-47ef7461-10fa-4e1d-9dc4-15912ef3bc7e.png)
![Screenshot (215)](https://user-images.githubusercontent.com/73010098/162575693-8cafffa3-4a3e-4307-84d9-1e92254ac56c.png)

 



