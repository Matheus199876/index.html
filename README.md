# index.html

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Extrair informações do PDF</title>
</head>
<body>
    <h2>📄 Extrair informações de um PDF</h2>
    <form action="/upload" method="post" enctype="multipart/form-data">
        <label for="file">Selecione um PDF:</label>
        <input type="file" name="file" accept="application/pdf" required>
        <br><br>
        <button type="submit">Enviar e Extrair</button>
    </form>
</body>
</html>
