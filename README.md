<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redireccionar a Formularios</title>
</head>
<body>
    <script>
        // Lista de URLs de formularios
        const forms = [
            "https://docs.google.com/forms/d/e/1FAIpQLScQYJf8Jy5K04PhKzL7Gmt5UsGKvy3PPfUzQWfX-jW7ANTcLA/viewform?usp=sf_link",
            "https://docs.google.com/forms/d/e/1FAIpQLSc1-el4UfeUpgxlc0rLpR_gcV_qLnhd51Ol6fmP-zSgv7sHNg/viewform?usp=sf_link",
            "https://docs.google.com/forms/d/e/1FAIpQLScwY0ZdwLA4HJgn5yz_c0VINGkVdnnZWEK6qE-Pa1Xp7sScEw/viewform?usp=sf_link",
            "https://docs.google.com/forms/d/e/1FAIpQLSfCijXrpl4njVywQIk8huAzNR8mxNDGlXLKP_r3Rm3FT67GEw/viewform?usp=sf_link",
            "https://docs.google.com/forms/d/e/1FAIpQLSekXmxdwoawVy1Ozq_JAipsjf99d8eV-dNWuCDVFJG8YkC--g/viewform?usp=sf_link",
            "https://docs.google.com/forms/d/e/1FAIpQLSfLfLHF73qHnczuFetVoCDOQqWOFLH9xZr-imZogopuLbhFyA/viewform?usp=sf_link",
            // Agrega más URLs según sea necesario
        ];

        // Redirigir a un formulario aleatorio
        window.location.href = forms[Math.floor(Math.random() * forms.length)];
    </script>
</body>
</html>
