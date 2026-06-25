<!DOCTYPE html>
<html>
<head>
<title>Laporan Bullying</title>
<style>
body{
font-family:Arial;
background:#f5f5f5;
padding:20px;
}
.container{
background:white;
padding:20px;
border-radius:10px;
max-width:600px;
margin:auto;
}
input,textarea,select{
width:100%;
padding:10px;
margin-top:5px;
margin-bottom:15px;
}
button{
padding:10px 20px;
}
</style>
</head>
<body>

<div class="container">

<h1>Laporan Bullying</h1>

<form action="https://formsubmit.co/emailkamu@gmail.com" method="POST">

<label>Nama (Opsional)</label>
<input type="text" name="nama">

<label>Kelas</label>
<input type="text" name="kelas" required>

<label>Jenis Bullying</label>
<select name="jenis">
<option>Verbal</option>
<option>Fisik</option>
<option>Cyberbullying</option>
<option>Pengucilan</option>
</select>

<label>Nama Terlapor</label>
<input type="text" name="terlapor" required>

<label>Kronologi</label>
<textarea name="kronologi" rows="6"></textarea>

<button type="submit">Kirim Laporan</button>

</form>

</div>

</body>
</html>