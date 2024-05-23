# Landingpage
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Batatas Congeladas</title>
    <style>
        body {font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; background-color: #f8f8f8;}
        .header, .footer {background-color: #333; color: white; padding: 20px; text-align: center;}
        .header nav a, .footer a {color: white; text-decoration: none; margin: 0 10px;}
        .container {max-width: 1200px; margin: 0 auto; padding: 20px;}
        .main {text-align: center; padding: 50px 0;}
        .main img {width: 100%; max-width: 600px; height: auto; border-radius: 10px;}
        .benefits, .testimonials {margin: 40px 0;}
        .benefits h2, .testimonials h2 {text-align: center; color: #333;}
        .benefit-item, .testimonial-item {margin-bottom: 20px;}
        .cta {background-color: #ff6600; color: white; padding: 10px 20px; text-decoration: none; display: inline-block; border-radius: 5px;}
        form {text-align: center;}
        form label {display: block; margin-top: 10px;}
        form input[type="text"], form input[type="email"], form input[type="tel"] {width: 80%; padding: 10px; margin-top: 5px; border: 1px solid #ccc; border-radius: 5px;}
        form input[type="submit"] {margin-top: 20px; padding: 10px 20px; border: none; background-color: #ff6600; color: white; border-radius: 5px; cursor: pointer;}
        .footer p {margin: 10px 0;}
    </style>
</head>
<body>
    <div class="header">
        <img src="logo.png" alt="Logo da Empresa">
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
        <img src="main-image.jpg" alt="Imagem das batatas">
        <a href="#form" class="cta">Cadastre-se agora e descubra como nossas batatas podem transformar seu supermercado!</a>
    </div>

    <div class="container benefits">
        <h2>Por que escolher nossas batatas congeladas?</h2>
        <div class="benefit-item">
            <h3>Qualidade Inquestionável</h3>
            <p>Garante satisfação dos seus clientes.</p>
        </div>
        <div class="benefit-item">
            <h3>Variedade de Cortes</h3>
            <p>Atende todas as preferências.</p>
        </div>
        <div class="benefit-item">
            <h3>Entrega Rápida e Gratuita</h3>
            <p>Em até 72 horas.</p>
        </div>
        <div class="benefit-item">
            <h3>Suporte de Marketing</h3>
            <p>Impulsiona as vendas diretamente nas gôndolas.</p>
        </div>
    </div>

    <div class="container testimonials">
        <h2>O que nossos clientes dizem?</h2>
        <div class="testimonial-item">
            <p>"As melhores batatas que já oferecemos. Nossos clientes adoram!" - João, Supermercado ABC</p>
        </div>
        <div class="testimonial-item">
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
</body>
</html>
