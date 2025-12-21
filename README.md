<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>7/F Sınıfı Galerisi</title>

<style>
body{
  margin:0;
  font-family:Arial, sans-serif;
  background:linear-gradient(#87cefa,#e0f6ff);
}

/* Başlık animasyon */
h1{
  text-align:center;
  padding:20px;
  animation:gel 1.5s ease;
}
@keyframes gel{
  from{opacity:0; transform:translateY(-30px);}
  to{opacity:1; transform:translateY(0);}
}

/* Galeri */
.galeri{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:15px;
  padding:20px;
}

/* Resimler */
.galeri img{
  width:100%;
  border-radius:12px;
  cursor:pointer;
  transition:.3s;
}
.galeri img:hover{transform:scale(1.05);}

/* Videolar */
video{
  width:100%;
  max-width:100%;
  border-radius:12px;
  background:black;
  display:block;
}
</style>
</head>

<body>

<h1>🎉 7/F Sınıfı Galerisi 🎉</h1>

<div class="galeri">
  <!-- RESİMLER -->
  <img src="resimler/resim1.jpeg">
  <img src="resimler/resim2.jpeg">
  <img src="resimler/resim3.jpeg">
  <img src="resimler/resim4.jpeg">
  <img src="resimler/resim5.jpeg">

  <!-- VİDEOLAR -->
  <video controls width="300">
  <source src="video4.mp4" type="video/mp4">
</video>

<video controls width="300">
  <source src="video2.mp4" type="video/mp4">
</video>



</video>
</body>
</html>

