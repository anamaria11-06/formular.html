# formular.html
<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <title>Formular de înregistrare</title>
</head>
<body>
  <h1>Formular de înregistrare</h1>
  <form>
    <label for="nume">Nume:</label><br>
    <input type="text" id="nume" name="nume" placeholder="Toma" required><br><br>

    <label for="prenume">Prenume:</label><br>
    <input type="text" id="prenume" name="prenume" placeholder="Ana" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" placeholder="exemplu@email.com" required><br><br>

    <label for="parola">Parola:</label><br>
    <input type="password" id="parola" name="parola" required><br><br>

    <label for="telefon">Număr de telefon:</label><br>
    <input type="number" id="telefon" name="telefon" placeholder="07xxxxxxxx" required><br><br>

    <input type="checkbox" id="termeni" name="termeni" required>
    <label for="termeni">Acceptați termenii și condițiile</label><br><br>

    <input type="submit" value="Trimite">
  </form>
</body>
</html>
