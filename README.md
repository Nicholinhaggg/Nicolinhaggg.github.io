<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Roupas, Bonecos e Posters</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Loja de Roupas, Bonecos e Posters</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Produtos</a></li>
                    <li><a href="#contact">Contato</a></li>
                    <li><a href="#youtube">YouTube</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="home-section">
        <div class="container">
            <h2>Bem-vindo à nossa loja!</h2>
            <p>Aqui você encontra as melhores roupas, bonecos e posters.</p>
            <img src="imagens/banner.jpg" alt="Banner da Loja">
        </div>
    </section>

    <section id="products" class="products-section">
        <div class="container">
            <h2>Produtos</h2>
            <div class="product">
                <h3>Roupas</h3>
                <img src="imagens/roupas.jpg" alt="Roupas">
                <p>Descrição das roupas.</p>
            </div>
            <div class="product">
                <h3>Bonecos</h3>
                <img src="imagens/bonecos.jpg" alt="Bonecos">
                <p>Descrição dos bonecos.</p>
            </div>
            <div class="product">
                <h3>Posters</h3>
                <img src="imagens/posters.jpg" alt="Posters">
                <p>Descrição dos posters.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <div class="container">
            <h2>Contato</h2>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message"></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <section id="youtube" class="youtube-section">
        <div class="container">
            <h2>Nosso Canal no YouTube</h2>
            <p>Confira nosso canal para mais novidades!</p>
            <a href="https://www.youtube.com/@nicholas_198" target="_blank">Visite nosso canal</a>
        </div>
    </section>
        <section id="support">
            <h2>Área de Suporte</h2>
            <p>Se precisar de ajuda ou tiver alguma dúvida, entre em contato conosco:</p>
            <form id="support-form">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required><br><br>
                
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Mensagem:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 Loja de Roupas, Bonecos e Posters. Todos os direitos reservados.</p>
        </div>
    </footer>

    <p>Criei esse site por causa da minha ex</p>

    <script src="scripts.js"></script>
</body>
</html>
