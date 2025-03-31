<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxo - Aluguel de Iates</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .cabecalho {
            background-color: #21272B;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .cabecalho img {
            width: 100px;
        }
        .menu {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
            background-color: #1A3243;
        }
        .menu a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .secao {
            padding: 20px;
            text-align: center;
        }
        .azul {
            background-color: #1BB4E8;
            color: white;
        }
        .dourado {
            background-color: #C6B07F;
            color: white;
        }
        .rodape {
            background-color: rgba(226, 215, 215, 0.911);
            text-align: center;
            padding: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="cabecalho">
        <img src="barco1.png" alt="Imagem de um Iate">
        <h1><span style="color: #1BB4E8;">Luxo</span><br>Aluguel de Iates</h1>
    </div>
    
    <nav class="menu">
        <a href="index.html">Página Inicial</a>
        <a href="Luxo_AL.html">Aluguel de Iate</a>
        <a href="Luxo_DT.html">Destino</a>
        <a href="Luxo_TR.html">Tripulação</a>
        <a href="Luxo_CT.html">Contato</a>
    </nav>
    
    <div class="secao">
        <h2>Bem-vindo ao Luxo Aluguel de Iates</h2>
        <img src="barcoprincipal.jpg" alt="Imagem de Iate">
    </div>
    
    <div class="secao azul">
        <p><strong>Você só encontra coisas boas se combinar luxo e paixão.</strong></p>
        <img src="barco2.png" alt="Imagem de Iate pequeno">
        <p>Ligue agora para agendar as férias da sua vida:</p>
        <a href="tel:0080000000" style="color: white; font-weight: bold;">(00) 8000-0000</a>
    </div>
    
    <div class="secao dourado">
        <h2>Nosso Destino</h2>
        <img src="destino.png" alt="Imagem de destino">
        <p>Explore os destinos mais luxuosos para sua viagem.</p>
    </div>
    
    <div class="secao dourado">
        <h2>Nossa Frota</h2>
        <img src="nossafrota.png" alt="Imagem da frota">
        <p>Conheça nossos iates modernos e sofisticados.</p>
        <div>
            <img src="barconossafrota1.jpg" alt="Iate 1">
            <img src="barconossafrota2.jpg" alt="Iate 2">
        </div>
    </div>
    
    <footer class="rodape">
        <p>&copy; 2025 Luxo Aluguel de Iates. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
