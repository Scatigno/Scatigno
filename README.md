<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo da Minha Loja Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .produto {
            background-color: #fff;
            border-radius: 5px;
            margin-bottom: 20px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .produto img {
            width: 100%;
            height: auto;
            display: block;
        }
        .produto .detalhes {
            padding: 20px;
        }
        .produto h2 {
            margin-top: 0;
            margin-bottom: 10px;
        }
        .produto .preco {
            font-size: 20px;
            color: #007bff;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="produto">
        <img src="imagem1.jpg" alt="Produto 1">
        <div class="detalhes">
            <h2>Produto 1</h2>
            <p class="preco">R$ 100,00</p>
        </div>
    </div>
    
    <div class="produto">
        <img src="imagem2.jpg" alt="Produto 2">
        <div class="detalhes">
            <h2>Produto 2</h2>
            <p class="preco">R$ 75,00</p>
        </div>
    </div>
    
    <div class="produto">
        <img src="imagem3.jpg" alt="Produto 3">
        <div class="detalhes">
            <h2>Produto 3</h2>
            <p class="preco">R$ 120,00</p>
        </div>
    </div>
</div>

</body>
</html>
