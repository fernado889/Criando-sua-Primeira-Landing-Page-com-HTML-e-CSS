# Criando-sua-Primeira-Landing-Page-com-HTML-e-CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo à Minha Landing Page!</h1>
        <p>Transforme suas ideias em realidade.</p>
        <a href="#cta" class="cta-button">Saiba Mais</a>
    </header>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Somos uma equipe dedicada a ajudar você a alcançar seus objetivos com nossos serviços personalizados.</p>
    </section>

    <section id="services">
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Consultoria Personalizada</li>
            <li>Desenvolvimento Web</li>
            <li>Marketing Digital</li>
        </ul>
    </section>

    <section id="cta">
        <h2>Pronto para Começar?</h2>
        <p>Entre em contato conosco hoje mesmo!</p>
        <a href="#contact" class="cta-button">Contato</a>
    </section>

    <footer>
        <p>&copy; 2024 Minha Empresa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

header {
    background: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

.cta-button {
    background: #FFD700;
    color: black;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 20px;
    margin: 10px;
    border: 1px solid #ccc;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
