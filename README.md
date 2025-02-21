# nyam_cat_prank.html.
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пранк с Ням Кэтом!</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            overflow: hidden;
        }
        img {
            width: 100%;
            max-width: 500px;
            animation: spin 5s infinite linear;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <img src="https://upload.wikimedia.org/wikipedia/ru/6/6b/NyanCat.gif" alt="Ням Кэт">
    <script>
        alert("Вы попались на пранк с Ням Кэтом!");
    </script>
</body>
</html>
