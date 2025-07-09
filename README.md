<!-- index.html -->
<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8" />
  <title>Reserver plass til filmen</title>
</head>
<body>
  <h1>FILMTITTEL</h1>
  <p>Velkommen! Reserver plass til førpremiere:</p>

  <form action="/reserver" method="POST">
    Navn: <input name="navn" required><br>
    E-post: <input type="email" name="epost" required><br>
    Antall plasser: <input type="number" name="plasser" min="1" required><br>
    <button type="submit">Reserver</button>
  </form>
</body>
</html>
