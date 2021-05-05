<!DOCTYPE html>
<html>
<head>
 <title>UTS PEMROGRAMAN WEB 2</title>
 <link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.7/css/select2.min.css" rel="stylesheet" />
 <script src="https://code.jquery.com/jquery-3.4.1.js" integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous"></script>
 <script type="text/javascript">
 $(document).ready(function() {
     $('#provinsi').select2({
      placeholder: 'Pilih Wilayah',
      allowClear: true
     });
 });
</script>
 <script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.7/js/select2.min.js"></script>
</head>
<body>
<form method="POST">
 <select id="Wilayah" name="Wilayah">
  <option ></option>
  <option value="DKI JAKARTA">DKI JAKARTA</option>
  <option value="JAWA BARAT">JAWA BARAT</option>
  <option value="JAWA TENGAH">BANTEN</option>
  <option value="JAWA TIMUR">JAWA TENGAH</option>
 </select>
</form>
<br>
      
      <h1 class="mt-4" align="center">  Data Pemantauan Covid 19 Wilayah Banten</h1>

            <div align="center" id="hasil"></div>
            <script>
                var waktu = new Date(); 
                document.getElementById("hasil").innerHTML = waktu;
            </script>
             <h2 class="mt-4" align="center"> FIRMANSYAH</h2> 
             <h4 align="center">181011401175</h4>
      <br>
      
      <span align="center">
       <table>
        <thead>
          <tr>
            <th>POSITIF</th>
            <th>DIRAWAT</th>
            <th>SEMBUH</th>
            <th>MENINGGAL</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>47.491</td>
            <td>1.478</td>
            <td>44.800</td>
            <td>1.213</td>
          </tr>
        
        </tbody>
      </table>
    </span>

<script type="text/javascript">
 $(document).ready(function() {
     $('#Wilayah').select2();
 });
</script>
</body>
</html>