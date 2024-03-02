# Peletakan JavaScript disarankan diatas </body>

## Kenapa?
- karena jika javascript diletakan seperti meletakan CSS nanti tampilan tidak akan muncul sebelum javascript selesai di jalankan

## Contoh 

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
  </head>
  <body>
    <h2 id="pesan">Selamat datang!</h2>
    <!-- meletakan diatas </body> -->
    <script>
    const tamu = prompt('Siapakah Anda?');
    alert('Selamat datang, ' + tamu + '!');
    </script>
  </body>
</html>
```