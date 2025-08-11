# site-acess-vel
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vendas de Ingressos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #f0c9ff, #e1a9ff);
            text-align: center;
            color: #333;
        }

        h1 {
            font-size: 3em;
            font-weight: bold;
            color: #333;
        }

        h2 {
            font-size: 2.5em;
            margin: 20px 0;
        }

        .content {
            margin: 30px 0;
        }

        .ingresso {
            font-size: 2em;
            font-weight: bold;
            color: #ff66cc;
            cursor: pointer;
        }

        .arrow {
            font-size: 3em;
            color: #ff66cc;
            animation: bounce 1s infinite;
        }

        .images {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 30px 0;
        }

        .images img {
            width: 250px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }
    </style>
</head>
<body>

    <h1>VENDAS DE INGRESSOS</h1>
    <h2>SHOW DA TAYLOR SWIFT</h2>

    <div class="images">
        <img src="https://link_da_imagem_da_taylor_1.jpg" alt="Taylor Swift 1">
        <img src="https://link_da_imagem_da_taylor_2.jpg" alt="Taylor Swift 2">
    </div>

    <div class="content">
        <p><strong>COMPRE SEU INGRESSO AQUI</strong></p>
        <a href="https://link_do_ingresso.com" class="ingresso">Clique Aqui!</a>
    </div>

    <div class="arrow">
        ↓
    </div>

</body>
</html>
