<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Portofolio Saya</title>

<style>
body {
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  text-align: center;
  margin: 0;
}
header {
  background: #2c3e50;
  color: white;
  padding: 20px;
}
section {
  background: white;
  margin: 15px;
  padding: 20px;
  border-radius: 10px;
}
img {
  width: 200px;
  border-radius: 10px;
}
button {
  padding: 10px 20px;
  border: none;
  background: #3498db;
  color: white;
  border-radius: 5px;
  cursor: pointer;
}
</style>
</head>

<body>

<header>
  <h1>Portofolio Saya</h1>
  <p>HTML • CSS • JavaScript</p>
</header>

<section>
  <h2>Tentang Saya</h2>
  <p>Ini portofolio sederhana untuk tugas sekolah.</p>
</section>

<section>
  <h2>Galeri</h2>
  <img src="https://pict.sindonews.net/dyn/850/pena/news/2024/09/17/156/1456851/10-gunung-terindah-di-indonesia-untuk-mendaki-nomor-2-punya-padang-edelweis-fso.jpg">
</section>

<section>
  <h2>Demo JavaScript</h2>
  <button onclick="klikSaya()">Klik Saya</button>
  <p id="hasil"></p>
</section>

<script>
function klikSaya() {
  document.getElementById("hasil").innerText =
    "JavaScript berhasil dijalankan!";
}
</script>

</body>
</html>
