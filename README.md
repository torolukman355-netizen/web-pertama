
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemesanan</title>
    <link rel="stylesheet" href="pesan.css">
</head>
<body>

  <form action="#" method="post">

<fieldset>
  <!-- data kostemer-->
<legend clas>PEMESANAN</legend>
<label for="nama">nama</label>
<input type="nama" name="nama" id="nama"><br><br>

<label for="telepon">Nomor telepon</label>
<input type="telepon" name="telepon" id="telepon"><br><br>

<label for="alamat">alamat</label>
<input type="alamat" name="alamat" id="alamat"><br><br>

<label for="nama">jumlah pemesanan</label>
<input type="nama" name="nama" id="nama"><br><br>

<!-- alat makan -->
alat makan: <br>
<input class="itula" type="checkbox" id="sendok" name="alat">
<label for="sendok">sendok</label><br>

<input type="checkbox" id="garpu" name="alat">
<label for="garpu">garpu</label><br>

<input type="checkbox" id="sedotan" name="alat">
<label for="sedotan">sedotan</label> <br><br>

<!-- pengiriman -->
<tr>
  <td>
    <select name="pengiriman" id="pengiriman">
      <option value="#">pengiriman</option>
      <option value="ilkom">pick up</option>
      <option value="ti">gosend</option>
    </select>
  </td>
</tr><br>
</fieldset>
<input type="submit" value="pesan sekarang">
  </form>
</body>
</html>
