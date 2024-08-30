# front-end_recupera-o2T_23_Matheus
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja MULTIELETRONICOS</title>
    <link rel="stylesheet" href="front-end_2A_2T_23_Matheus.css">
</head>

<body>
    <header>
        <h1>Bem-vindo à Loja MULTIELETRONICOS</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#sobre">Sobre Nós</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#testemunhos">Testemunhos</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Sobre Nós</h2>
            <p>Somos uma loja especializada em multieletrônicos, oferecendo uma vasta gama de produtos tecnológicos de qualidade.</p>
        </section>

        <section id="produtos">
            <h2>Nossos Produtos</h2>
            <!-- Produto 1 -->
            <article>
                <img src="ventilador.jpg" alt="Ventilador Portátil" width="300">
                <h3>Ventilador Portátil Com Iluminação Umidificador Climatizador</h3>
                <p>Experimente o alívio imediato do calor com o Mini Ventilador Portátil Umidificador de Ar Condicionado LED.</p>
                <p><strong>Preço:</strong> R$100,00</p>
                <button>Comprar</button>
            </article>

            <!-- Produto 2 -->
            <article>
                <img src="caixa_termica.jpg" alt="Caixa Térmica" width="300">
                <h3>Caixa Térmica Soprano Preta 32 Litros</h3>
                <p>Capacidade para armazenar cerca de 50 latas de cerveja de 350ml, ideal para festas.</p>
                <p><strong>Preço:</strong> R$150,00</p>
                <button>Comprar</button>
            </article>

            <!-- Produto 3 -->
            <article>
                <img src="smartphone.jpg" alt="Smartphone" width="300">
                <h3>Smartphone XYZ 128GB</h3>
                <p>Desempenho de alta qualidade com câmera avançada e armazenamento de 128GB.</p>
                <p><strong>Preço:</strong> R$1.200,00</p>
                <button>Comprar</button>
            </article>
        </section>

        <section id="contato">
            <h2>Contato</h2>
            <p>Entre em contato conosco pelo email: <a href="mailto:contato@multieletronicos.com">contato@multieletronicos.com</a></p>
            <p>Ou ligue para: (11) 1234-5678</p>
            <form>
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome">
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem"></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>

        <section id="faq">
            <h2>FAQ</h2>
            <p>Encontre respostas para as perguntas mais frequentes.</p>
        </section>

        <section id="testemunhos">
            <h2>O que dizem nossos clientes</h2>
            <p>"Produto excelente, super recomendo!" - João</p>
            <p>"Atendimento rápido e eficiente!" - Maria</p>
        </section>
    </main>

    <footer>
        <p><strong>&copy; 2024 Loja MULTIELETRONICOS. Todos os direitos reservados.</strong></p>
        <p>Nosso compromisso é com sua satisfação. Visite-nos regularmente para novidades e ofertas exclusivas!</p>
    </footer>
</body>

</html>