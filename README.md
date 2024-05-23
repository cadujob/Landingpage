<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Batatas Congeladas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="header">
        <img src="images/logo.png" alt="Logo da Empresa">
        <nav>
            <a href="#about">Sobre</a> | 
            <a href="#products">Produtos</a> | 
            <a href="#testimonials">Depoimentos</a> | 
            <a href="#contact">Contato</a>
        </nav>
    </div>

    <div class="container main">
        <h1>Aumente a lucratividade do seu supermercado com as melhores batatas congeladas do mercado!</h1>
        <p>Batatas crocantes por fora, macias por dentro, entregues gratuitamente em até 72 horas.</p>
        <img src="images/batatas.jpg" alt="Imagem das batatas">
        <a href="#form" class="cta">Cadastre-se agora e descubra como nossas batatas podem transformar seu supermercado!</a>
    </div>

    <div class="container benefits">
        <h2>Por que escolher nossas batatas congeladas?</h2>
        <div class="benefit-item">
            <img src="images/qualidade.jpg" alt="Qualidade Inquestionável">
            <h3>Qualidade Inquestionável</h3>
            <p>Garante satisfação dos seus clientes.</p>
        </div>
        <div class="benefit-item">
            <img src="images/variedade.jpg" alt="Variedade de Cortes">
            <h3>Variedade de Cortes</h3>
            <p>Atende todas as preferências.</p>
        </div>
        <div class="benefit-item">
            <img src="images/entrega.jpg" alt="Entrega Rápida e Gratuita">
            <h3>Entrega Rápida e Gratuita</h3>
            <p>Em até 72 horas.</p>
        </div>
        <div class="benefit-item">
            <img src="images/marketing.jpg" alt="Suporte de Marketing">
            <h3>Suporte de Marketing</h3>
            <p>Impulsiona as vendas diretamente nas gôndolas.</p>
        </div>
    </div>

    <div class="container testimonials">
        <h2>O que nossos clientes dizem?</h2>
        <div class="testimonial-item">
            <img src="images/joao.jpg" alt="João, Supermercado ABC">
            <p>"As melhores batatas que já oferecemos. Nossos clientes adoram!" - João, Supermercado ABC</p>
        </div>
        <div class="testimonial-item">
            <img src="images/maria.jpg" alt="Maria, Supermercado XYZ">
            <p>"A entrega rápida e o suporte de marketing fizeram a diferença." - Maria, Supermercado XYZ</p>
        </div>
    </div>

    <div class="container">
        <h2>Não perca tempo, aumente suas vendas agora!</h2>
        <form id="form">
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="company">Empresa:</label><br>
            <input type="text" id="company" name="company"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="phone">Telefone:</label><br>
            <input type="tel" id="phone" name="phone"><br>
            <input type="submit" value="Quero conhecer as batatas congeladas!">
        </form>
    </div>

    <div class="footer">
        <p>Contato: (31) 1234-5678 | Email: contato@empresa.com.br</p>
        <p>Siga-nos: <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">LinkedIn</a></p>
        <p>&copy; 2024 Empresa. Todos os direitos reservados.</p>
    </div>

    <script src="scripts/main.js"></script>
</body>
</html>
