<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Digital - airiaMCode</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            text-align: center;
            color: #e74c3c;
        }
        .menu-section {
            margin-bottom: 30px;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .item-name {
            font-weight: bold;
        }
        .item-price {
            color: #e74c3c;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>airiaMCode</h1>
        <h2>Menu Digital</h2>

        <!-- Entradas -->
        <div class="menu-section">
            <h2>Entradas</h2>
            <div class="menu-item">
                <span class="item-name">Bruschetta Clássica</span>
                <span class="item-price">R$ 18,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Carpaccio de Filé</span>
                <span class="item-price">R$ 25,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Bolinhos de Bacalhau</span>
                <span class="item-price">R$ 22,00</span>
            </div>
        </div>

        <!-- Pratos Principais -->
        <div class="menu-section">
            <h2>Pratos Principais</h2>
            <div class="menu-item">
                <span class="item-name">Filé Mignon ao Molho Madeira</span>
                <span class="item-price">R$ 68,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Risoto de Cogumelos</span>
                <span class="item-price">R$ 45,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Salmão Grelhado</span>
                <span class="item-price">R$ 55,00</span>
            </div>
        </div>

        <!-- Bebidas -->
        <div class="menu-section">
            <h2>Bebidas</h2>
            <div class="menu-item">
                <span class="item-name">Vinho Tinto (taça)</span>
                <span class="item-price">R$ 15,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Refrigerante (lata)</span>
                <span class="item-price">R$ 6,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Suco Natural</span>
                <span class="item-price">R$ 10,00</span>
            </div>
        </div>

        <!-- Sobremesas -->
        <div class="menu-section">
            <h2>Sobremesas</h2>
            <div class="menu-item">
                <span class="item-name">Cheesecake de Frutas Vermelhas</span>
                <span class="item-price">R$ 20,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Petit Gateau</span>
                <span class="item-price">R$ 18,00</span>
            </div>
            <div class="menu-item">
                <span class="item-name">Sorvete Artesanal</span>
                <span class="item-price">R$ 12,00</span>
            </div>
        </div>
    </div>
</body>
</html>
