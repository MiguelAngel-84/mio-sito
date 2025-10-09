```html
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Il mio sito personale</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #58e39e;
            text-align: center;
            padding: 50px;
        }
        img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        h1 {
            color: #333;
        }
        p {
            color: #555;
            font-size: 18px;
        }
        /* --- Stile della tabella --- */
        table {
            margin: 40px auto; /* centra la tabella */
            border-collapse: collapse;
            width: 80%;
            max-width: 600px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
        }
        td a {
            text-decoration: none;
            color: #0077cc;
            font-weight: bold;
        }
        td a:hover {
            color: #ff6600;
        }
    </style>
</head>
<body>
    <img src="foto.jpeg" alt="La mia foto">
    <h1>Ciao, sono Miguel!</h1>
    <p>Benvenuto nel mio sito personale.<br>
    sono ancora in <strong>working progress</strong>.</p>

    <!-- TABELLA DEI LINK -->
    <table>
        <tr>
            <td><a href="https://www.google.com" target="_blank">Progetto 1</a></td>
            <td><a href="https://www.youtube.com" target="_blank">YouTube</a></td>
            <td><a href="https://it.wikipedia.org" target="_blank">Wikipedia</a></td>
        </tr>
        <tr>
            <td><a href="https://www.github.com" target="_blank">Progetto 2</a></td>
            <td><a href="https://www.facebook.com" target="_blank">Facebook</a></td>
            <td><a href="https://www.twitter.com" target="_blank">Twitter</a></td>
        </tr>
        <tr>
            <td><a href="https://www.instagram.com" target="_blank">Progetto 3</a></td>
            <td><a href="https://www.linkedin.com" target="_blank">LinkedIn</a></td>
            <td><a href="https://www.tiktok.com" target="_blank">TikTok</a></td>
        </tr>
        <tr>
            <td><a href="https://www.apple.com" target="_blank">Progetto 4</a></td>
            <td><a href="https://www.microsoft.com" target="_blank">Microsoft</a></td>
            <td><a href="https://www.amazon.it" target="_blank">Amazon</a></td>
        </tr>
        <tr>
            <td><a href="https://www.netflix.com" target="_blank">Progetto 5</a></td>
            <td><a href="https://openai.com" target="_blank">OpenAI</a></td>
            <td><a href="https://chat.openai.com" target="_blank">ChatGPT</a></td>
        </tr>
    </table>
</body>
</html>
