<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>Status Iseng-iseng</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>

<center>
<script>
window.setTimeout("waktu()",1000); 
function waktu() { 
        var tanggal = new Date(); 
        setTimeout("waktu()",1000); 
        document.getElementById("jam").innerHTML = tanggal.getHours(); 
        document.getElementById("menit").innerHTML = tanggal.getMinutes();
        document.getElementById("detik").innerHTML = tanggal.getSeconds();
    }
</script>
<div id="jam-digital">
    <div id="hours">
        <p id="jam"></p>
    </div>
    <div id="titik1">
    	<p>:</p>
    </div>
    <div id="minute">
        <p id="menit"></p>
    </div>
    <div id="titik1">
    	<p>:</p>
    </div>
    <div id="second">
        <p id="detik"></p>
    </div>
</div>
	<h1>Selamat Kepo :D</h1>&nbsp;&nbsp;
	<ul class="float">
		<li><a href="minggu1.html" title="Klik Untuk Melihat Tugas Minggu 1">Minggu 1</a></li>
		<li><a href="minggu2.html" title="Klik Untuk Melihat Tugas Minggu 2">Minggu 2</a></li>
		<li><a href="minggu3.html" title="Klik Untuk Melihat Tugas Minggu 3">Minggu 3</a></li>
	</ul>
	
	

</center>
</body>
</html>
