# Tomas
gimtadienio sveikinimas
<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gimtadienio sveikinimas</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            padding: 20px;
        }
        h1 {
            color: #ff4081;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 20px;
        }
    </style>
    <script>
        console.log("Puslapis kraunamas...");
        document.addEventListener("DOMContentLoaded", function() {
            console.log("Puslapis pilnai užsikrovė.");
        });
    </script>
</head>
<body>
    <h1>Simute, su gimtadieniu!</h1>
    <p>Tegul šie metai būna kupini džiaugsmo, meilės ir visko, kas tau teikia laimę.</p>
    <p>Norėjau įteikti tau dovanėlę, kuri suteiktų dar daugiau džiaugsmo ir laimės, tačiau dovanėlė pasiklydo keliaudama iki tavęs ir teks truputį pakentėti...</p>
    <img src="img.jpg" alt="Dovana" onload="console.log('Paveikslėlis sėkmingai įkeltas.')" onerror="console.log('Nepavyko įkelti paveikslėlio.')">
</body>
</html>
